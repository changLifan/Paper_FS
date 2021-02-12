# Paper_FS
…or create a new repository on the command line
echo "# Paper_FS" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/changLifan/Paper_FS.git
git push -u origin master
                
…or push an existing repository from the command line
git remote add origin https://github.com/changLifan/Paper_FS.git
git branch -M master
git push -u origin master




（1） 本地git首次连接远程github仓库
github.com 个人中心创建远程仓库Repository
本地创建文件夹作为git仓库,在文件夹内打开git bash脚本程序执行git init命令
依次执行
git init
git pull https://github.com/changLifan/Paper_FS.git
git remote add master https://github.com/changLifan/Paper_FS.git
git add . 
git commit -m "首次提交信息"
git remote add origin https://github.com/changLifan/Paper_FS.git
git branch -M master
git push -u origin master


（2）配置环境之后，第n次提交：
git status
git add .
git commit -m "论文信息"
git push -u origin master

