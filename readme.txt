git checkout -- filename  撤销工作区修改，回到上次commit或add时的状态
git reset --hard commitID
git reset HEAD filename   unstage command
git rm filename;git commit -m MESG;
git push [-u] origin master 注意-u参数是关联远程分支与本地分支
Github地址格式 https[或git]://github.com/sealeaf/proName
git checkout -b branchname 相当git branch branchname;git checkout branchname
git merge branchname  当前在master，合并子分支(Fast-Forward)
git merge --no-ff -m MERGEMSG branchname  普通模式合并，建立新的commit
git branch -d branchname  删除分支
git stash;git stash list;git stash pop;  保存工作现场
git remote [-v];  查看远程信息
git push origin master;	推送分支
git checkout -b branchname origin/branchname;从远程抓取本地不存在的新分支
git branch --set-upstream branchname origin/branchname 链接本地与远程分支
//tag operation
git tag -a tagname [-m] "说明文字" commitID  在当前commit上打标签
git tag  查看标签
git show tagname
git tag -d tagame  删除标签
git push origin tagname;git push origin --tags  后者是推送所有标签
git push origin :refs/tags/tagname  删除远程标签
