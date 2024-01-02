---
title: link
date: 2023-10-07 18:08:29
type: "link"
---
```
To https://github.com/Virligri11/ncutest.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/Virligri11/ncutest.git'
```

```
First Do this ...

git fetch origin master
git merge  master

Then, do this ...

git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp

Now everything works well.
```