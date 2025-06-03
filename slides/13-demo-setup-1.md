---
---

# Demo Setup: Step 1

<div class="mt-8">
<h2>Generate MFE Apps (Webpack-based)</h2>

```bash
# Generate host application
nx g @nx/angular:host apps/shell --prefix=ng-mf

# Generate remote with automatic linking
nx g @nx/angular:remote apps/myremote1 --prefix=ng-mf --host=shell
```

<div v-click class="mt-8 p-4 bg-blue-100 dark:bg-blue-900 rounded">
  <h3>💡 What Happens:</h3>
  <ul>
    <li>Creates host and remote applications</li>
    <li>Sets up module federation config</li>
    <li>Links remotes to host automatically</li>
  </ul>
</div>
</div>