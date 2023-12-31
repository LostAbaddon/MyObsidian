---
作者: LostAbaddon
tags:
  - 工具
  - 技巧
---
![](../images/obsidiansync.jpg)

可以使用Github来实现Obsidian的同步、发布、订阅以及网页显示，而无需使用Obsidian的官方收费服务。

# 同步

## 方案1

可以在一个Vault中设置一个Public目录和一个Private目录，两个目录各自是一个Git Repo，分别放公开或私有的文档。
这个方案简单直白，但缺点是Obsidian的设置以及插件无法同步过来。

## 方案2

将Vault目录作为一个Repo，它的可访问性是公开或者私有都可以。然后将可访问性不同的目录作为submodule的Repo引入。
这样设置与插件可以在最外层的Repo中共享（当然，可以在.gitignore中将.trash目录放进去，这个看各自需求），而不同可访问性的目录作为submodule，并不会被一起同步给其他订阅者。

## 方案3

将Vault设为Git之外的同步软件（比如微云、Dropbox、阿里网盘等）的同步目录，而且是私有的。然后将其中若干目录作为公开Git Repo。
缺点是私有目录的控制比较受限，无法做到完全隔离。

# 订阅

订阅者可以直接在Git上Follow公开的Repo，或者在有邀请的情况下订阅私有的Repo。
同时，订阅者也可以Pull Request将自己的想法与修改提交给所有者，由所有者决定是否并入这些新资料或修改。

# 发布

由于是Markdown格式，在Github上本身就可以以网页的形式浏览。如果不能的话，也可以自行制作一个简单的本地服务器来本地化显示渲染后的网页。