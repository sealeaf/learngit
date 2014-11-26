git checkout -- filename  撤销工作区修改，回到上次commit或add时的状态
git reset --hard commitID
git reset HEAD filename   unstage command
git rm filename;git commit -m MESG;
git push [-u] origin master 注意-u参数是关联远程分支与本地分支
Github地址格式 https[或git]://github.com/sealeaf/proName
git checkout -b branchname 相当git branch branchname;git checkout branchname
git merge branchname  当前在master，合并子分支
git branch -d branchname  删除分支
