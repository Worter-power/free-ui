# git 常用命令

echo "# vue-pages-demo" >> README.md

1.配置用户名和邮箱
    git config --global user.name "xuhaiyan"
    git config --global user.email "haiyan.xu.vip@gmail.com"
2.拉去远程项目
    git clone git@github.com:billyanyteen/github-services.git
3.仓库初始化：
    git init
4.生成快照并存入项目索引：
    指定文件 git add README.md 
    全部 git add
5.项目索引提交：
    git commit -m "first commit"
6.添加远端repo：
    git remote add origin https://github.com/Worter-power/vue-pages-demo.git
7.更新远程更新到本地：
    git pull origin master
8.推送本地更新到远程：
    git push -u origin master

git add # 将工作区的修改提交到暂存区
git commit # 将暂存区的修改提交到当前分支
git reset # 回退到某一个版本
git stash # 保存某次修改
git pull # 从远程更新代码
git push # 将本地代码更新到远程分支上
git reflog # 查看历史命令
git status # 查看当前仓库的状态
git diff # 查看修改
git log # 查看提交历史
git revert # 回退某个修改