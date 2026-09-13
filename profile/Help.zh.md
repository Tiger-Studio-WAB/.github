# GitHub 相关说明

[English](Help.md) · [中文](Help.zh.md) · [Deutsch](Help.de.md)

## 克隆项目

以下是克隆项目的分步说明。

1. 下载 [GitHub CLI](https://cli.github.com/) 并完成登录认证
2. 打开你要克隆的项目
3. 点击绿色的 **Code** 按钮
4. 选择 Local 和 GitHub CLI
5. 复制命令
6. 打开终端（macOS / Linux），或 CMD / PowerShell（Windows）
7. 建议不要克隆到磁盘根目录，请先输入 `cd documents`
8. 粘贴刚才复制的命令并回车执行
9. 仓库会复制到当前目录下，文件夹名称通常与仓库名相同

# Git

## 下载

Git 是我们用于项目管理的开源版本控制系统。  
开始参与项目之前，请先下载 [Git](https://git-scm.com/install/mac)。

## 推送与拉取

请先按照[下载](Help.zh.md#下载)完成 Git 安装。

### 推送

终端：`git push`

我们建议通过 IDE 或专门软件来推送。用终端推送和提交需要较多命令，也不容易编辑提交说明。

### 拉取

终端：`git pull`

指定分支：`git pull 'remote_name' 'branch_name'`
