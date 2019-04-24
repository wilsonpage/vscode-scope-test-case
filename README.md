### Steps to reproduce

1. `npm install`
2. `npm run checkjs:serviceWorker`

### Issue

Errors on known worker only API `self.skipWaiting()`

### Resolution

Need a way to define the environment/scope of `worker.js` to `ServiceWorkerGlobalScope`, without changing scope of `app.js` from `Window`.
