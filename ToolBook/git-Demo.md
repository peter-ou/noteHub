# git和GitHub的关联使用



<!-- GFM-TOC -->
* [git如何提交内容到GitHub仓库中](#git如何提交内容到GitHub仓库中)








# git如何提交内容到GitHub仓库中

```
//add只是将文件或目录添加到了index暂存区
//使用commit可以实现将暂存区的文件提交到git本地仓库，[message]为备注信息
// 将本地git仓库内容提交到关联好了的 GitHub 仓库 
git add .
git commit -m "message"
git push origin master
```