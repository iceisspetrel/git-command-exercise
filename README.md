git 命令练习

git init 本地仓库初始化git<br/>
git add [filename | *] 添加或者提交某个文件 或者全部文件,将文件放入暂存区<br/>
git commit -m "str"将暂存区的文件提交到分支<br/>
git status 查看仓库状态 哪些文件有改变<br/>
git diff [filename] 对比文件<br/>
git log 查看git提交日志 <br/>
git reset --hard [~index | commitid] 恢复到倒数第几个版本或者是指定提交id的版本<br/>
git reset head [filename] 将某个文件回退到分支的最新版本中<br/>
git reflog 查看git版本变更命令日志<br/>
git checkout -- [filename] 舍弃某个文件的修改，回退到暂存区的内容或者是分支的内容
git remote add origin git@github.com:iceisspetrel/git-command-exercise 将本地仓库与远程仓库关联
git push -u origin master 将本地仓库内容提交到远程仓库 第一次时需要使用-u，之后就不用了
