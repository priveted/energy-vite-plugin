# Energy Vite Plugin

Plugin for the correct operation of the Energy framework

#### Installation

```
npm i priveted/energy-vite-plugin
```

### Configure vite.config.js 
```js
import { defineConfig } from 'vite';
import energy from 'energy-vite-plugin';
 
export default defineConfig({
    plugins: [
        energy([
            // 'resources/styles/main.css'
            'resources/styles/main.scss', // If sass is installed (recommended)
            'resources/js/main.js',
        ]),
    ],
});
```

### Add to "resources/js/main.js"
```js
import '../styles/main.scss'
// Your application code
// ....
```