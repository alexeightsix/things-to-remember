```
Prevent pushing to “main” locally with this git config snippet.

In ~/.gitconfig
[branch "main"]
pushRemote = "no_push" 
 
[remote "no_push"] 
push = "do_not_push" 
url = "do_not_push"`
```
