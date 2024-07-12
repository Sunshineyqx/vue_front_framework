```cmd
npm create vue@latest
....是/否
cd xxx
npm install
```




```vue
// main.js
import 'element-plus/dist/index.css'
import { createApp } from 'vue'
import App from './App.vue'
import ElementPlus from 'element-plus'

const app = createApp(App)
app.use(ElementPlus)
app.mount('#app')
```
