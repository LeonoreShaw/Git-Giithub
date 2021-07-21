## **Git 命令**

### git配置 （==git config==）

用法： `git config –global user.name “[name]”` 

用法： `git config –global user.email “[email address]”` 

此命令分别设置要与您的提交一起使用的作者姓名和电子邮件地址。

![Git 配置命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/1-9.png)

### git初始化 （==git init==)

用法： `git init [repository name]`

 

此命令用于启动一个新的存储库。

![GitInit 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/2-6.png)

### git 克隆 (==git clone==)

用法： `git clone [url]` 

此命令用于从现有 URL 获取存储库。

![Git 克隆命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/4-4.png)

### 添加	(==git add==)

用法： `git add [file]` 

此命令将文件添加到暂存区。

![Git 添加命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/5-4.png)

用法： `git add *` 

此命令将一个或多个添加到暂存区。

![Git 添加命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/6-3.png)

### 提交 (==git commit==)

用法： `git commit -m “[ Type in the commit message]”` 

此命令在版本历史记录中永久记录或快照文件。

![Git 提交命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/7-3.png)

用法： `git commit -a` 

此命令提交您使用 git add 命令添加的任何文件，并提交您从那时起更改的所有文件。

![Git 提交命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/8-2.png)

### git差异	(==git diff==)

用法： `git diff` 

此命令显示尚未暂存的文件差异。

![Git Diff 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/9-2.png)

 `Usage: git diff –staged` 

此命令显示暂存区中的文件与当前最新版本之间的差异。

![Git Diff 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/10-2.png)

用法： `git diff [first branch] [second branch]` 

此命令显示了提到的两个分支之间的差异。

![Git Diff 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/43.png)

### 重置	(==git reset==)

用法： `git reset [file]` 

此命令取消暂存文件，但保留文件内容。

![Git 重置命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/11-1.png)

用法： `git reset [commit]` 

此命令在指定提交后撤消所有提交并在本地保留更改。

![Git 重置命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/14-1.png)

用法： `git reset –hard [commit]` 此命令丢弃所有历史记录并返回到指定的提交。

![Git 重置命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/13-1.png)

### 状态 (==git status==)

用法： `git status` 

此命令列出所有必须提交的文件。

![Git 状态命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/15-1.png)

### ==git rm==

用法： `git rm [file]` 

此命令从您的工作目录中删除文件并分阶段删除。

![Git Rm 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/16-2.png)

### git日志 (==git log==)

用法： `git log` 

此命令用于列出当前分支的版本历史记录。

![Git 日志命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/18.png)

用法： `git log –follow[file]` 

此命令列出文件的版本历史记录，还包括文件的重命名。

![Git 日志命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/19.png)

### git 显示 (==git show==)

用法： `git show [commit]` 

此命令显示指定提交的元数据和内容更改。

![Git 显示命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/20.png)

### git标签 (==git tag==)

用法： `git tag [commitID]` 

此命令用于为指定的提交提供标签。

![Git 标签命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/22.png)

### git 分支 (==git branch==)

用法： `git branch` 

此命令列出当前存储库中的所有本地分支。

![Git 分支命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/23.png)

用法： `git branch [branch name]` 

此命令创建一个新分支。

![Git 分支命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/24.png)

用法： `git branch -d [branch name]` 

此命令删除功能分支。

![Git 分支命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/25.png)

### ==git checkout==

用法： `git checkout [branch name]` 

此命令用于从一个分支切换到另一个分支。

![Git Checkout 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/27.png)

用法： `git checkout -b [branch name]` 

此命令会创建一个新分支并切换到该分支。

![Git Checkout 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/28.png)

### 合并 (==git merge==)

用法： `git merge [branch name]` 

此命令将指定分支的历史记录合并到当前分支中。

![Git 合并命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/31-1.png)

### git远程 (==git remote==)

用法： `git remote add [variable name] [Remote Server Link]` 

此命令用于将本地存储库连接到远程服务器。

![Git 远程命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/32.png)

### 推 (==git push==)

用法： `git push [variable name] master` 

此命令将 master 分支的已提交更改发送到您的远程存储库。

![Git 推送命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/33.png)

用法： `git push [variable name] [branch]` 

此命令将分支提交发送到您的远程存储库。

![Git 推送命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/34.png)

用法： `git push –all [variable name]` 

此命令将所有分支推送到您的远程存储库。

![Git 推送命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/36.png)

用法： `git push [variable name] :[branch name]` 

此命令删除远程存储库上的分支。

![Git 推送命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/37.png)

### 拉 (==git pull==)

用法： `git pull [Repository Link]` 

此命令获取远程服务器上的更改并将其合并到您的工作目录。

![Git Pull 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/38.png)

### ==git stash==

用法： `git stash save` 

该命令临时存储所有修改过的跟踪文件。

![Git Stash 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/39.png)

用法： `git stash pop` 

此命令恢复最近隐藏的文件。

![Git Stash 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/40.png)

用法： `git stash list` 

此命令列出所有隐藏的变更集。

![Git Stash 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/44.png)

用法： `git stash drop` 

此命令会丢弃最近存储的变更集。

![Git Stash 命令 - Git 命令 - Edureka](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/42.png)