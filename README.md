# github-exception-handling
git命令常见异常处理

//初始化
1、设置用户名  git config --global user.name 'github userName'
2、设置邮箱  git config --global user.email '...@qq.com'
3、对项目初始化git  git init
4、查看状态  git status
5、查看设置信息  git config --list

//文件操作
1、创建文件夹  mkdir filename
2、创建文件  touch file.txt
3、提交到缓存区，（方便修改和撤回）git add projectName
4、提交到git仓库  git commit -m ‘描述文件’

//删除文件
1、删除本地文件 rm -rf dir/file
2、删除git仓库文件  git rm -r --cached dir/file    git rm -r dir/file
3、提交修改信息 git commit -m ‘描述文件’
4、更新远程仓库 git push


//push 上传到远程仓库新建文件夹（必须要有子文件）
1、提交新文件到缓存区   git add 新文件
2、提交到本地git仓库  git commit -m "描述文件"
3、提交到github远程仓库 git push (git push origin master)

//pull从远程仓库下载到本地
1、直接下载 git pull
