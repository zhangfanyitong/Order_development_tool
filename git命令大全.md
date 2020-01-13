# 1.基本操作流程
- `git status `: 查看暂存区的文件状态。
- `git add 文件名 ` : 将特定的文件存到暂存区，`git add . `是将所有修改的文件存到暂存区。
- `git commit "提交说明" `：将暂存区的文件提交到本地仓库。
- `git remote -v ` :查看当前远程仓库的所有分知名。
- `git remote add  别名 远程地址 `：创建别名，不用每次都push 远程地址名。
- `git push 别名 分支名 ` ： 将本地仓库的代码推送到远程仓库
- `git clone 远程地址` ：将远程仓库的代码clone到本地，并更名为origin
---
# 2.代码历史库管理
- `git log `:查看仓库的历史记录
- `git reflog`: 推荐的查看历史记录
- ` git reset --hard 局部索引值` ：将版本会到某一版(**前提：文件存在状态提交到了本地库**)
---
# 3.分支管理
- `git branch 分支名` ：创建分支。
- `git branch -v`:查看分支。
- `git branch -d 分支名称`：删除指定的本地分支。
- `git branch -D 分支名称`：强制删除指定的本地分支。
- `git checkout 分支名` ：切换到分支。
- `git checkout -b 分支名` ：创建并切换到指定分支。
- 合并分支：
    1. 切换到接受修改的分支：`git checkout  分支名`。
    2. 将`分支名`合并到所在分支:`git merage 分支名 `
 