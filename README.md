# Git 技术栈学习
- Git 版本控制软件
-- local repository Remote Repository

- GitHub 免费提供远端仓库的网站
-- Gitlab Bitbucket
-- 公开 私有

- 准备工作
-- 安装Git VsCode AI Agent GitHub注册
-- git init 初始化 .git子文件夹
-- .gitignore 仓库文件不受Git管理

- Commit 提交
-- Discard Changes 放弃还没Commit的文件更改
-- reset 把仓库强制回退到某个历史状态，不适合多人协作分支
-- revert 生成反向commit抵消某次commit，适合多人协作分支
-- Commit ID 又叫Commit Hash 长ID 短ID

- Branch 分支
-- main/master 主干分支
-- feature 特性分支 可基于分支创建分支
-- Merge Commit 分支合并回主干
-- Head 指向哪个分支就指向哪个分支最新一次Commit，也可指向某一次历史提交，即分离头指针状态

- WorkTree 工作树
-- claude --worktree 分支名

- Conflict 冲突
-- 手工处理

- Git Areas git分区
-- Working Directory 工作区
-- Local Repositoy 本地仓库
-- Remote Repository 远程仓库
-- Staging/Index area 暂存区
-- git clone 把远端仓库保存到本地同时创建本地存储库和本地工作目录
-- git add(把本地文件保存到暂存区) + git commit(把暂存区的所有改动提交到本地仓库 ) 把本地工作区的改动提交到本地仓库;VsCode 的Commit合并了两个Git命令简化了操作;不加入暂存区默认全部commit
-- git push 将本地仓库改推送到远端存储库；需要管理员授予权限
-- git pull 将远端存储库的最新改动更新并合并到本地
    git merge git fetch 将远端的最新改动合并进本地工作区

