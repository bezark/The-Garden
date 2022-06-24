---
publish: true
tags: [ref/obsidian/plugins/templeter]
---

`tp.file.create_new(template: TFile ⎮ string, filename?: string, open_new: boolean = false, folder?: TFolder)`

- `template`: Either the template used for the new file content, or the file content as a string.  
- `filename`: The filename of the new file, defaults to "Untitled".  
- `open_new`: Whether to open or not the newly created file. **Warning**: if you use this option, since commands are executed asynchronously, the file can be opened first and then other commands are appended to that new file and not the previous file.  
- `folder`: The folder to put the new file in, defaults to obsidian's default location.