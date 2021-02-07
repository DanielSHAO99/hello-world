# hello-world
just try repository
2017-8-17 22:52:47
later this day, netmusic played,maybe xuezhiqian,don't know name of this song.try github


2018-5-9

now it is 2018 i almost forget how to do this  guiding work. i use this very little time .
hah,my poor english

2018年05月21日

了解了一下selenium的事情
from selenium import webdriver
通过driver=webdriver.Firefox()初始化一个浏览器
dirver.get("http://www.example.com")
打开一个页面，注意get后面的url一定要是以http://开始。

关闭页面是driver.close()
可以操作页面，搜索页面，打字等
keys是模拟按键输入操作

2021年01月13日16:47:21
git push origin 本地分支名：远程不存在要创建的分支名
2021年02月06日18:48:57
git rebase 优化commit历史，commit -amend也可以
2021年02月07日11:28:30
vim 输入大写G，跳转到文件末尾， 输入小写gg，跳转到文件开始
2021年02月07日11:20:05
1，用来测试git rebase的使用
2, git rebase 我在测试
3,git rebase 应该是拉取最新的‘base'代码，把当前的改动放入拉取后的提交，这样就会是一条直线

practice makes perfect
4, 有点晕
origin分支， dev分支，远程均有，
dev分支基于的origin分支是 a, 然后dev进行了b，c两次提交
origin在dev分支 进行b，c分支开发的时候，进行 d提交
此时在dev分支上进行 rebase origin dev分支 则就是，将d提交添加入dev分支的历史中，并把之后的b，c提交’串好‘，变基，其提交历史不会分叉，是一条线
git rebase origin后，若有冲突，则首先处理冲突，进入对应的文件，处理<<< >>>  ===符号
使用git add -u, 使用git rebase --continue继续rebase,过程结束不需要commit
git add -u 将更新加入暂存
添加amend的使用说明
git commit --amend 将此次提交和上次提交放在一起
