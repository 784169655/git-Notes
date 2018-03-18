# git-Notes

1.download resource to local 
     上git官网Clone with HTTPS 克隆地址，然后进入目标文件夹 使用命令git clone 克隆地址 ,checkout 到本地.
2.使用git commit
    2.1首先进入到checkout 到本地的目录里， 然后使用git status 查看工作区的状态 
    promote:test xiaowei$ git status
    On branch master
    Your branch is up-to-date with 'origin/master'.

    Untracked files:
    (use "git add <file>..." to include in what will be committed)

    ../.DS_Store
    ./

    nothing added to commit but untracked files present (use "git add" to track)
    promote:test xiaowei$ 
    
    2.2 提交为空，但是存在未跟踪的文件 
    使用提示命令 git add 文件名  可以使用文件存入暂存区
      
    2.3再使用git status 查看工作空间的状态,说可以使用 git reset 命令把文件撤出暂存区
    
    On branch master
    Your branch is up-to-date with 'origin/master'.

    Changes to be committed:
    (use "git reset HEAD <file>..." to unstage)

	  new file:   1517802427314.jpg
    
    2.4 但并不想撤消，而是想提交  使用git commit  然后输入提交描述
    
    2.5然后把提交到本地的文件  使用git push 进行发布到git hub，进行同步
    
    2.6 使用git status 说没有文件需要提交,这时候进入git hub，发现文件已经提交。 


    
