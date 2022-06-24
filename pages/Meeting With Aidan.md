---
publish: true
tags: itp/class/notes, edit
---
[[2021-03-09]]

Had thoughts about my [[Kinetic Project - Wind Powered Website]] and [[DFM Project]]

[[Solar Powered Website]]
https://threejs.org/docs/index.html#api/en/constants/Textures
```jsx
// load a texture, set wrap mode to repeat
const texture = new THREE.TextureLoader().load( "textures/water.jpg" );
texture.wrapS = THREE.RepeatWrapping;
texture.wrapT = THREE.RepeatWrapping;
texture.repeat.set( 4, 4 );
```

CC0 and Texture Haven
