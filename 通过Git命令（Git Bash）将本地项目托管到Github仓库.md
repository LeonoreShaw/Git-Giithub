# 通过Git命令（Git Bash）将本地项目托管到Github仓库

>一个项目一个.git





## 1、`git init`—————本地Git初始化

```cd```进入项目路径

```git
git init
```

此命令用于启动一个新的存储库

![image-20210721164340007](https://github.com/LeonoreShaw/Images/blob/ReadmeFilesImages/Git-GitHub/image-20210721164340007.png?raw=true)



## 2、`git add`—————将文件添加到暂存区

将添加项目文件添加到工作区后

![image-20210721165215893](https://github.com/LeonoreShaw/Images/blob/ReadmeFilesImages/Git-GitHub/image-20210721165215893.png?raw=true)

```git
git add [file name]
```

此命令将文件添加到暂存区

![image-20210721165308071](https://github.com/LeonoreShaw/Images/blob/ReadmeFilesImages/Git-GitHub/image-20210721165308071.png?raw=true)

```git
git add *
```

此命令将一个或多个添加到暂存区

![image-20210721165340450](https://github.com/LeonoreShaw/Images/blob/ReadmeFilesImages/Git-GitHub/image-20210721165340450.png?raw=true)



## 3、`git commit`—————将暂存区文件提交到Git库分支

```git
git commit -m “提交说明”
```

此命令在版本历史记录中永久记录或快照文件。

![image-20210721170115273](https://github.com/LeonoreShaw/Images/blob/ReadmeFilesImages/Git-GitHub/image-20210721170115273.png?raw=true)

```git
git commit -a
```

此命令提交您使用 git add 命令添加的任何文件，并提交您从那时起更改的所有文件。

![image-20210721171220360](https://github.com/LeonoreShaw/Images/blob/ReadmeFilesImages/Git-GitHub/image-20210721171220360.png?raw=true)



## 4、`git remote`—————将本地存储库连接到远程服务器

```git
git remote add [variable name] [Remote Server Link]
```

此命令用于将本地存储库连接到远程服务器。

![image-20210721172203532](https://github.com/LeonoreShaw/Images/blob/ReadmeFilesImages/Git-GitHub/image-20210721172203532.png?raw=true)



## 5、`git push`—————推送到您的远程存储库

```git
`git push [variable name] master
```

此命令将 `master`分支的已提交更改发送到您的远程存储库。

![image-20210721172434043](https://github.com/LeonoreShaw/Images/blob/ReadmeFilesImages/Git-GitHub/image-20210721172434043.png?raw=true)

```git
 git push [variable name] [branch]
```

此命令将`branch`分支提交发送到您的远程存储库。



```git
git push –all [variable name]
```

此命令将所有分支推送到您的远程存储库。



```git
git push [variable name] :[branch name]
```

此命令删除远程存储库上的分支。







## 其他常用Git命令

* ### ==**`ls`**==

显示当前目录所有文件



* ### **`git clone `**

用法： `git clone [url]` 

此命令用于从现有 URL 获取存储库。



* ### **`git status `**

此命令列出所有必须提交的文件。

* `git branch [branch name]` 

此命令创建一个新分支。

* `git branch -d [branch name]` 

此命令删除功能分支。



### * **`git checkout `**

 `git checkout [branch name]` 

此命令用于从一个分支切换到另一个分支。

 `git checkout -b [branch name]` 

此命令会创建一个新分支并切换到该分支。



### * **`git merge `**

用法： `git merge [branch name]` 

此命令将指定分支的历史记录合并到当前分支中。



* ### **`git branch `**

此命令列出当前存储库中的所有本地分支。



* ### **`git log `**

此命令用于列出当前分支的版本历史记录。

`git log –follow[file]` 

此命令列出文件的版本历史记录，还包括文件的重命名。



* ### **`git remot -v `**

此命令列出当前连接的远程服务器仓库



* ### **` git remote rm origin `**

此命令断开当前连接的远程服务器仓库

