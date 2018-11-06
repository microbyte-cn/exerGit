如果本地有一个git目录，
不是从 服务器  clone的  前提下  是否能 上传到git呢？

在服务器上创建了一个空的仓库，没有任何内容
https://github.com/shiminzheng/exerGit.git


添加远程仓库
$ git remote add gh https://github.com/shiminzheng/exerGit.git


查看结果
$ git remote -v


把本地的上传到服务器
git push -u origin master

========================================================

echo "# exerGit" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/shiminzheng/exerGit.git
git push -u origin master

========================================================

git remote add origin https://github.com/shiminzheng/exerGit.git
git push -u origin master

========================================================
这里的修改是为了分支练习


