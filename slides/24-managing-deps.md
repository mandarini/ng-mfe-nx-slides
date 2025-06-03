---
---

# Managing Shared Dependencies

<div class="mt-8">
<h2>The Trade-off: Sharing vs Bundle Size</h2>

```typescript
// Fine-tune what gets shared across your MFE apps
shared: (name, config) => {
  // Don't share lodash - enable tree-shaking instead
  if (name === 'lodash') return false; 
  
  // Share React as singleton (required!)
  if (name === 'react') return config;
  
  return config; // Share everything else by default
}
```

<div v-click class="mt-8 grid grid-cols-2 gap-4">
  <div class="p-4 border rounded">
    <h3>Result</h3>
    <p>Each app bundles only the lodash functions it uses (5kb vs 100kb)</p>
  </div>

  <div class="p-4 border rounded">
    <h3>Documentation</h3>
    <p><a href="https://nx.dev/concepts/module-federation/faster-builds-with-module-federation">Faster Builds with Module Federation</a></p>
  </div>
</div>

<div v-click class="mt-8 p-4 bg-blue-100 dark:bg-blue-900 rounded">
  <h3>💡 When to Share vs Bundle</h3>
  <ul>
    <li>Share: Core frameworks, state management, singleton behavior needed</li>
    <li>Bundle: Libraries with good tree-shaking (lodash, date-fns, utilities)</li>
  </ul>
</div>
</div>