---
---

# How Nx Serves Your Host

<div class="mt-8">
<h2>Behind the Scenes Magic:</h2>

<div class="grid grid-cols-2 gap-4 mt-6">
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

<div v-click class="mt-8 p-4 bg-blue-100 dark:bg-blue-900 rounded">
  <h3>💡 Pro Tip</h3>
  <p>Nx handles all the complexity - you focus on building features!</p>
</div>
</div>