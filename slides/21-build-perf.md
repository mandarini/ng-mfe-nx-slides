---
---

# Build Performance Deep Dive

<div class="mt-8">
<h2>Timing Comparison:</h2>

```bash
# Webpack build timing
time nx build shell

# Rspack build timing  
time nx build shell2
```

<div v-click class="mt-8 p-4 bg-blue-100 dark:bg-blue-900 rounded">
  <h3>Real World Results:</h3>
  <ul>
    <li>Webpack: 45-60 seconds</li>
    <li>Rspack: 5-8 seconds</li>
    <li>~90% reduction in build time</li>
  </ul>
</div>

<div v-click class="mt-8 text-center text-xl">
  <em>Order of magnitude improvements in DX!</em>
</div>
</div>