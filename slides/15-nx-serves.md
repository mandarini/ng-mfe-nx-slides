---
---

# How Nx Serves Your Host

<div class="mt-8">
<h2>Behind the Scenes Magic:</h2>

<div class="space-y-6">
  <div v-click class="p-4 border rounded">
    <h3>1. Discovery</h3>
    <p>Finds all remotes the host depends on</p>
  </div>

  <div v-click class="p-4 border rounded">
    <h3>2. Parallel Builds</h3>
    <p>Builds static remotes simultaneously</p>
  </div>

  <div v-click class="p-4 border rounded">
    <h3>3. Server Setup</h3>
    <p>Creates proxy servers for each remote port</p>
  </div>

  <div v-click class="p-4 border rounded">
    <h3>4. Host Launch</h3>
    <p>Serves host with webpack-dev-server</p>
  </div>
</div>
</div>