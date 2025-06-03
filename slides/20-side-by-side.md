---
---

# Side-by-Side Performance

<div class="mt-8">
<h2>Run Both Simultaneously:</h2>

```bash
# Terminal 1: Webpack
nx serve shell --devRemotes=myremote1

# Terminal 2: Rspack  
nx serve shell2
```

<div v-click class="mt-8 grid grid-cols-2 gap-4">
  <div class="p-4 border rounded">
    <h3>Webpack</h3>
    <ul>
      <li>Initial build: ~30s</li>
      <li>HMR update: ~2s</li>
      <li>Memory usage: Higher</li>
    </ul>
  </div>

  <div class="p-4 border rounded">
    <h3>Rspack</h3>
    <ul>
      <li>Initial build: ~3s</li>
      <li>HMR update: ~200ms</li>
      <li>Memory usage: Lower</li>
    </ul>
  </div>
</div>
</div>