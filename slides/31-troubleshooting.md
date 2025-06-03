---
---

# Troubleshooting Guide

<div class="mt-8">
<h2>Common Issues & Solutions:</h2>

<div class="grid grid-cols-3 gap-6 mt-6">
  <div v-click class="p-4 border rounded">
    <h3>🔄 HMR Not Working</h3>
    <ul class="text-sm mt-2">
      <li>Check devRemotes flag</li>
      <li>Verify port configuration</li>
      <li>Clear browser cache</li>
    </ul>
  </div>

  <div v-click class="p-4 border rounded">
    <h3>📦 Build Failures</h3>
    <ul class="text-sm mt-2">
      <li>Check dependency versions</li>
      <li>Verify module federation config</li>
      <li>Review shared dependencies</li>
    </ul>
  </div>

  <div v-click class="p-4 border rounded">
    <h3>🔌 Remote Loading Issues</h3>
    <ul class="text-sm mt-2">
      <li>Check remote URLs</li>
      <li>Verify CORS settings</li>
      <li>Review network requests</li>
    </ul>
  </div>
</div>

<div v-click class="mt-8 p-4 bg-blue-100 dark:bg-blue-900 rounded">
  <h3>💡 Debug Tools</h3>
  <p>Use browser dev tools network tab to inspect remote loading</p>
</div>
</div>