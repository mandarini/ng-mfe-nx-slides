---
---

# Dev Server Options

<div class="mt-8">
<h2>Selective Development Mode:</h2>

```bash
# All remotes static (fast startup)
nx serve shell

# Specific remotes in dev mode (HMR)  
nx serve shell --devRemotes=myremote1,myremote2
```

<div v-click class="mt-12 grid grid-cols-2 gap-4">
  <div class="p-4 border rounded">
    <h3>Static Mode</h3>
    <ul>
      <li>Fastest startup</li>
      <li>Best for UI work</li>
      <li>No remote rebuilds</li>
    </ul>
  </div>

  <div class="p-4 border rounded">
    <h3>Dev Mode</h3>
    <ul>
      <li>Full HMR support</li>
      <li>Live remote updates</li>
      <li>Best for active development</li>
    </ul>
  </div>
</div>
</div>