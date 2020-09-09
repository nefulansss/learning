#rebase和merge的区别
merge是两个分支和其公共祖先做一个三方合并
rebase是做变基操作：以另一个分支为基础，将当前分支追加到其后面；例如：
```$xslt
git checkout experiment
git rebase master
#以master为基础，experiment合并到master的后面
```
