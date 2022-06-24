---
tags: itp/class/blog
publish: true
---


For [[The Shape of Me]] I got a [[Raspberry Pi]] to pull a [[GitHub]] repo at boot, which was fairly straight forward.

I'm not entirely sure if this is the PROPER way to do it, but it seemed to work for me. I think...


Here's the bash script I used.

```bash
#!/bin/bash

echo "Pulling repo..."

cd /home/john/Shape_of_Me

git pull

node index.js
```

I then just had this script run at boot with the `crontab`:
```
@reboot [path to shell script]
```

I just needed to also install the `git` and  `github` cli tools:
`sudo apt-get install git`
`sudo apt-get install gh`

and then set up github with `gh auth`

I THINK this worked, but critically it MAY only work when you ssh into the pi, I'm not 100% sure...   `¯\_(ツ)_/¯`
