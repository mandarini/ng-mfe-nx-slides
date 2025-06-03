---
layout: two-cols
---

# Module Federation: Key Concepts

<div class="space-y-6">
  <div v-click class="p-4 border rounded">
    <h3 class="text-xl mb-4">Host</h3>
    <p>Application that consumes federated modules</p>
  </div>

  <div v-click class="p-4 border rounded">
    <h3 class="text-xl mb-4">Remote</h3>
    <p>Application that exposes modules to be consumed</p>
  </div>

  <div v-click class="p-4 border rounded">
    <h3 class="text-xl mb-4">Federated Module</h3>
    <p>Any JavaScript code shared at runtime</p>
  </div>
</div>

::right::

<div v-click class="h-full flex items-center justify-center">

```mermaid
graph TD
  H[Host] --> R1[Remote 1]
  H --> R2[Remote 2]
  H --> R3[Remote 3]
```

</div>