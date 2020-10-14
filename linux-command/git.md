#rebase和merge的区别
参考：
https://git-scm.com/book/zh/v2/Git-%E5%88%86%E6%94%AF-%E5%8F%98%E5%9F%BA
https://git-scm.com/book/zh/v2/Git-%E5%88%86%E6%94%AF-%E5%88%86%E6%94%AF%E7%9A%84%E6%96%B0%E5%BB%BA%E4%B8%8E%E5%90%88%E5%B9%B6#_basic_merging
merge是两个分支和其公共祖先做一个三方合并
rebase是做变基操作：以另一个分支为基础，将当前分支追加到其后面；例如：
```$git
git checkout experiment
git rebase master
#以master为基础，experiment合并到master的后面
```

```$git
#查看配置
git config user.name
git config user.email
#配置
git config -global user.name 'xxxx'
git config -global user.email 'xxxx@ss'
#生成密钥
ssh-key -t rsa -C '上面的邮箱'

```



