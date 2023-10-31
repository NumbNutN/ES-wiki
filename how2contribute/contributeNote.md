# 如何贡献

如果您是第一次贡献一个 github 仓库可以[参考](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project)
> 简而言之：
> 1. fork 该仓库
> 2. 新建一个分支（请起一个有意义的名字），并在新建的分支上作出修改&commit
> 3. 提出 pull request

> 如果您有写入权限（您是被邀请的）可以不必 fork。
> 只需在该仓库新建一个分支，作出修改&commit，提出 pull request

1. 如果您发现内容有不正确的，可以提出 Issue，我们欢迎您提出 pull request 帮助我们改进内容
2. 有新的您觉得值得注意的问题可以直接提出 pull request，我们将会尽量将其加入我们的内容
3. 请尽量保证您的内容正确，语言尽可能利于理解，能让大家更快的理解内容

## 项目结构

```
.
├── LICENSE
├── README.md
├── dir1(chapter 1) （章节）
│   ├── contents.md （目录）
│   ├── topic1.md   （话题）
│   ├── topic2.md
│   └── ...
└── dir2(chapter 2)
    ├── contents.md
    └── topic.md
```

我们希望：
- 每个章节有它对应的一个文件夹
- 同一个章节中，不同话题可以有各自的`.md`文件
- 当话题**真的无法**归入已有文件夹，请新建一个章节，并在 `README.md` 中加入新加章节的目录链接
- 创建一个新的话题(`.md 文件`)请在目录中添加链接，指向新的话题
- 如果增加的经验内容较少可以在已有的 `.md` 文件中添加新的段落，并在目录中添加链接指向该段落
- 为文件或文件夹起名时，使用有意义的英文名称
- 每个章节中可以加入一个 topic 叫 `miscellaneous.md` 来存储小的难以归类的建议
