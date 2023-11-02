# 关于网站

## 这是什么

ES-Wiki是由UESTC 嵌入式工作室搭建的用于问题记录和学习内容的站点。

由于互联网上关于嵌入式开发的知识过于零散，在工作室成员的学习过程中发现很多“弯路”，故本站点致力于为读者提供嵌入式开发的学习指南及资料，以及记录一些坑点

## 如何使用

使用pip安装本项目所需依赖：

```
pip install mkdocs mkdocs-material
```

本地调试：(winodws上应该需要使用`python -m `命令)

```shell
mkdocs serve
```

## 如何贡献

fork本仓库，然后更改需要更改的markdown文件或者新建新的markdown文件，md文件应均存在于docs目录

然后根据`mkdocs.yml`文件提示修改`mkdocs.yml`文件即可

运行命令：（windows需要使用`python -m `命令）

```shell
mkdocs build
```

完成构建之后推送

``` 
mkdocs gh-deploy
```

并提交pr（写明修改内容和相关信息）

## 纠错勘误

如发现错误可以提交Issues或者提出pr或者联系工作室负责人

