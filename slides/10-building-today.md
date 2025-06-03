---
---

# What We're Building Today

<div class="mt-8">
<h2>Architecture Overview:</h2>

```mermaid {scale: 0.8}
graph TD
    A[Shell Host ← Webpack 4200] --> B[Remote 1 HMR Demo]
    A --> C[Remote 2 Components]
    A --> D[Remote 3 Services]
    E[Shell2 Host ← Rspack 4300] --> F[Same Architecture]
    F --> G[Zero Config Changes]
```

<div v-click class="mt-8 p-4 bg-green-100 dark:bg-green-900 rounded">
  <h3>💡 Key Point</h3>
  <p>Same architecture, better performance with Rspack</p>
</div>
</div>