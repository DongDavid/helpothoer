增加默认主机
origin 主机别名 可以任意字符
https://.....git 主机地址
git remote add origin https://github.com/example.git
修改主机origin的host
git remote set-url origin https://....git
删除主机origin
git remote rm origin


查看主机详情
git remote -v
克隆到本地
git clone origin


推送更新到origin主机上的master分支
git push -u origin master


获取主机上的更新
git fetch origin master  //把远程仓库同步到本地仓库，但是不修改代码


git pull origin master  //同步到本地 并合并  等于fetch+merge
