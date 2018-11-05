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
 
> ## 使用SSH

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
 
	
# 工作流
> ##
	
# 其他
	echo <内容> >> <文件名>
	
	cat <文件名>
	
	
 
