1.全局配置用户名、邮箱
git config --global user.name=“gitlab用户名”
git config --global user.email="gitlab邮箱";
2.拉取远端代码；
git clone + 远端仓库地址；
3.创建分支并切换分支；
git branch checkout +分支名 
4.切换分支 ;
git checkout + 分支名
5.查看本地分支；
git branch  
6.查看远端分支
git branch -a 
7.查看修改文件状态；
git status 
8. 添加到本地缓存文件
git add + 文件路径 （.代表全部）
9.添加修改注释；
git commit -m"修改了什么东西"
10.拉取远端最新代码并与本地分支合并
git pull 
11. 拉取远端最新代码不与本地分支合并
git fetch(后面如果需要合并，看12) 
12. 合并代码
git merge + --no-ff(参数表示不删除日志 --no-ff：不使用fast-forward方式合并，保留分支的commit历史）+ --squash (表示合并多个提交记录合并成一次)；
13 .将本地代码推送到远端;
git push 
14. 查看提交记录日志
git log 
