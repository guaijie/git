# github

	study github directive

# download github

	直接进入官网下载安装包
 
# github GUI(sourcetree)

[sourcetree](https://www.sourcetreeapp.com)
 
# 配置用户信息

> ## 全局用户配置 

 	git config --global user.name <username>

  	git config --global user.email <email &gt>

 	git config --list 查看全局配置


# 创建一个仓库

> ##  初始化版本库

	git init
	
> ## 添加文件到版本库

	git add ./<文件名>（添加到暂存区）
	
	git commit -m（添加到版本库）
	
> ## 查看仓库状态

	git status
	
> ## 将暂存区的版本回归到工作区
	
	git reset HEAD <文件名>
	
> ## 清空工作区
	
	git checkout ./<文件名>（让修改的文件回到修改前）
	
> ## 打印历史commit记录
	
	git log
	
> ## 打印未来commit 记录

	git reflog

> ## 回滚
	
	git reset [--hard] <commit id> [暂存区和版本库都]回滚
	
> ## 移除指定文件

	git rm <文件名>

# 工作流

![git 工作流](https://github.com/guaijie/github/blob/master/img/QQ%E6%88%AA%E5%9B%BE20181105154643.png "工作流")

# 远程仓库

> ## SSH keys

	ssh-keygen -t rsa -C "myemail" (生成ssh key 在C盘Users的当前账户目录中）
	
> > ### 查看是否授权成功
	
	ssh -T git@github.com
	
> ## git pull <主机名> <分支>:<本地分支>
	
	从远程仓库中拉取指定分支的数据并与本地分支合并
	
> ## git fetch <主机名> <分支>
	
	从远程仓库中拉取指定分支的数据
	
> ## git clone <主机名> <分支>

	从远程仓库中克隆指定分支的数据
	
> ## git push [-u] <主机名> <分支> 

	[设置默认主机] 并推送到远程的指定分支
	
> ## git remote add <主机名>  

	添加主机名（默认为origin）
	
> ## git config core.sparsecheckout true(用于迁出指定的文件夹)

	开启sparse checkout 模式
	
> ## echo libs >> .git/info/sparse-checkout  

	告诉Git哪些文件或者文件夹是你真正想Check Out的

# 标签管理（标签回滚）
 
> ## 查看所有标签

	git tag
	
> ## 创建标签

	git tag <tagname>
	
> ## 创建有描述信息的标签
 
	git tag -a name -m ""
	
> ## 删除标签

	git tag -d name
	
> ## 标签发布

	git push <主机名> <tagname>
	
# 分支管理
 
> ## 查看所有分支
	
	git branch

> ## 切换分支

	git checkout <branchname>
	
> ## 合并分支
	
	git merge <branchname>
	
> ## 删除分支
 	
	git branch -d <branchname>
	
# 其他
	echo <内容> >> <文件名> （添加信息到指定文件中）
	
	cat <文件名> （查看文件内容）
	
	vi <文件名> (打开指定文件)
	
	touch <文件名> （新建文件）
	
 
 
 
