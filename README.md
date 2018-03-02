# monoame-preloader
## A light js script for loading array of images based on promise
## to use
---
```
npm i monoame-preloader
```

To load array of images:

```javascript
import preloader from 'monoame-preloader'
preloader.load([
  'url1',
  'url2'
]).then(()=>{
  console.log("image all preloaded!")
}).catch(()=>{
  console.log("image preload fail.")
})
```