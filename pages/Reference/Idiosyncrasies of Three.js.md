---
publish: true
tags: ref/js/three
---
Idiosyncrasies about Three.js
- Texture Loader works Synchronously
- Model Loader is asynchronous and needs a call back function.
- All the examples use javascript modules:
	- ![[Pasted image 20210218161835.png]]
	- It allows them to say "import"
	- But there's a workaround:
		- Go to js folder instead of jsm and import THAT and then call it with THEEE.Whatever... see RTSS discord for example
		- 
