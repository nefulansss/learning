#加行号
:set number

:set nonumber

#删除
x    删除光标下的字符 ("dl" 的缩写)

X    删除光标前的字符 ("dh" 的缩写)

D    从当前位置删除到行尾 ("d$" 的缩写)

dG    删除到文件末

dgg    删除到文件首

#查看文件末尾/开头 num行
tail -n num file
head -n num file 

#跳转指定行 n
ngg / nG    #n行

#撤销
a. 按小写字母「u」，撤销上一步的更改操作；

b. 按大写字母「U」，撤销整行的更改操作；