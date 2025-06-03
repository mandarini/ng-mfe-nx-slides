---
---

# Sharing Strategy Guide

<div class="mt-8">
<h2>When to Share vs Bundle:</h2>

<div class="grid grid-cols-2 gap-4">
  <div v-click class="p-4 border rounded">
    <h3>Share These ✅</h3>
    <ul>
      <li>Core frameworks (Angular, React)</li>
      <li>State management (NgRx, Redux)</li>
      <li>Common UI libraries</li>
      <li>Shared business logic</li>
    </ul>
  </div>

  <div v-click class="p-4 border rounded">
    <h3>Bundle These 📦</h3>
    <ul>
      <li>Utility libraries (lodash, date-fns)</li>
      <li>Tree-shakeable packages</li>
      <li>Infrequently used modules</li>
      <li>Version-sensitive packages</li>
    </ul>
  </div>
</div>

<div v-click class="mt-8 p-4 bg-blue-100 dark:bg-blue-900 rounded">
  <h3>💡 Pro Tip</h3>
  <p>Use the shared callback to fine-tune what gets shared vs bundled:</p>

```typescript
shared: (name, config) => {
  if (name === 'lodash') return false; // Bundle
  if (name === 'react') return config; // Share
  return config; // Default sharing behavior
}
```
</div>
</div>