# _Images
## 简介

markdown图床系统

本系统运转过程如下：

1. 使用typora的图片复制功能在写作过程中将所有插入图片复制到指定图床文件夹
2. 通过\_commit.sh脚本\_replace.py脚本实现替换指定文件夹下md文件图片路径，并将图床文件夹提交到github

## 使用方式

打开_commit.sh脚本即可，记得修改\_commit.sh和\_replace.py里的路径

## 未来方向

- [x] 整合2和3，在修改路径的同时一键git 

