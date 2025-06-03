---
---

# What is Module Federation?

## Runtime Code Sharing Revolution

<div class="mt-8">
Module Federation allows <mark>sharing code between applications at runtime</mark> - not build time!
</div>

```typescript {all|1-2|4-5}
// Remote exposes component
exposes: { './HelloComponent': './src/hello' }

// Host consumes at runtime  
import HelloComponent from 'remote/HelloComponent';
```

<div v-click class="mt-8">
<h3>Key Benefits:</h3>
<ul>
  <li>Share code without rebuilding</li>
  <li>Load components on demand</li>
  <li>True runtime modularity</li>
</ul>
</div>