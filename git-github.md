创建仓库：git init  
把指定文件提交到暂存区：git add xxx  
把所有文件都提交到暂存区：git add -A  
查看文件状态：git status  
提交到历史区：git commit -m'文件信息'  
查看提交记录：git log  
#####git和github同步  
查看所有的关联信息：git remote -v  
建立关联：git remote add origin xxx [远程仓库git地址]  
移出关联：git remote remove xxx  
拉取信息：git pull origin master  
推送信息：git push origin master