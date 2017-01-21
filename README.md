# Plugin Worker
WebWorker plugin for [SystemJS](https://github.com/systemjs/systemjs)
# Usage
Install the plugin

```jspm install worker=github:simoncast/plugin-worker```

Load a worker

```javascript
import Worker from './worker.js!worker';

// API differs little bit from regular Worker
// path to worker is already given in the import
const worker = new Worker();
worker.postmessage('hello world');
```
