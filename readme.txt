配置789030rui

git config --global user.name "13539422949"
git config  --global user.email "13539422949@139.com"

建立一个文件夹
进入文件夹

初始化
git init


git add readme.txt
git commit -m "注释信息"

状态
git status 

git log

git log --pretty=oneline

回退到上一个版本
git reset --hard HEAD^
回退到上上个版本
git reset --hard HEAD^^
回退到上100个版本
git reset --hard HEAD~100
回退到具体某一个版本
git reset --hard 具体的版本号

git reflog

撤销 ， 
git checkout -- filename

--上传到github
创建sshkey
sshkeygen -t rsa -C "13539422949@139.com"

信息
Enter file in which to save the key (/c/Users/Administrator/.ssh/id_rsa):


验证链接
ssh -T git@github.com


关联
git remote add origin  git@github.com:13539422949/2949.git

删除关联
git remote rm origin git@github.com:13539422949/2949.git

推送本地库内容到远程库
git push origin master 

拉取远程库到本地
git pull origin master --allow-unrelated-histories
