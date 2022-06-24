---
publish: true
tags: ref/js/node
aliases: [node.js]
tags: []
---

- [Tom's Node Examples](https://github.com/tigoe/NodeExamples)
  id:: 619d02e9-f9e7-4ca7-8b44-8fafa2d7de28
# How to Kill a Node Script
- Ctrl+Z suspends it, which means it can still be running.
  
  Ctrl+C will actually kill it.
  
  you can also kill it manually like this:
  
  ```bash
  ps aux | grep node
  ```
  
  Find the process ID (second from the left):
  
  ```bash
  kill -9 PROCESS_ID
  ```
  
  This may also work
  
  ```bash
  killall node
  ```