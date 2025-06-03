---
---

# Managing Shared Dependencies

<div class="mt-8">
<h2>Fine-Tuning Shared Libraries:</h2>

```typescript
// Opt out of sharing for tree-shaking
shared: (name, config) => {
  if (name === 'lodash') return false; // Bundle separately
  return config; // Share by default
}
```

<div v-click class="mt-8 grid grid-cols-2 gap-4">
  <div class="p-4 border rounded">
    <h3>When to Share</h3>
    <ul>
      <li>Common frameworks (Angular, React)</li>
      <li>Shared state management</li>
      <li>Core utilities</li>
    </ul>
  </div>

  <div class="p-4 border rounded">
    <h3>When to Bundle</h3>
    <ul>
      <li>Large utilities (lodash)</li>
      <li>Infrequently used modules</li>
      <li>Version-sensitive packages</li>
    </ul>
  </div>
</div>
</div>