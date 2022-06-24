---
publish: true
tags: ref/js/three
---
[hrdihaven](https://hdrihaven.com/hdris/) is a good site

Use CubeTextureLoader
```js
const scene \= new THREE.Scene(); scene.background \= new THREE.CubeTextureLoader() .setPath( 'textures/cubeMaps/' ) .load( \[ 'px.png', 'nx.png', 'py.png', 'ny.png', 'pz.png', 'nz.png' \] );
																													 
																														   
																														   ```
They should be named that way because they are negative x positive x, negative y, positive y etc....


[HDRI to CubeMap](https://matheowis.github.io/HDRI-to-CubeMap/)
