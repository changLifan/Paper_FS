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


配置环境之后，第n次提交：
git status
git add .
git commit -m "论文信息"
git push -u origin master

