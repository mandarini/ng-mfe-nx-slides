---
---

# Demo Setup: Step 2

<div class="mt-8">
<h2>Convert to Rspack (The Magic!)</h2>

```bash
# Convert existing Angular app to use Rspack
nx g @nx/angular:convert-to-rspack

# Same MFE architecture + lightning builds!
```

<div v-click class="mt-8 grid grid-cols-2 gap-4">
  <div class="p-4 border rounded">
    <h3>Before</h3>
    <ul>
      <li>Webpack build time: ~30s</li>
      <li>Standard HMR</li>
    </ul>
  </div>

  <div class="p-4 border rounded">
    <h3>After</h3>
    <ul>
      <li>Rspack build time: ~3s</li>
      <li>Lightning fast HMR</li>
    </ul>
  </div>
</div>
</div>