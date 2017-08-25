光速达中央控制器（简称：中控）使用文档

## 说明
目前文档内容正在整理当中

## 贡献

我们欢迎所有用户提交 PR 或 issue 为我们贡献或者修正错误，衷心感谢您的贡献。

**贡献方法及注意事项**：

- `fork` 这个项目
- 修改或增加文档内容
- 提交修改并发起 `Pull Request`

## 内部贡献

为避免在所提交 PR 中出现与修改内容无关的 Merge pull request 的 commits，推荐使用以下流程提交 PR：

1. 本地切换到 master 分支
1. rebase
1. 新建分支 new branch 进行修改
1. 提交 PR，如有相关的 issue 在注释中增加 `Fixes #???`。问号为 issue 的编号。

合并 PR 时，如果 commits 历史不重要，可以选择 Squash and Merge 来合并，合并后删除相关的分支。


## 目录结构

```
├── README.md                          // 说明文档
├── archive                            // 已下线存档的文档，请勿更新
├── custom                             // 文档页面样式及 JavaScript 代码
├── images                             // 文档中引用的所有图片
├── md                                 // 临时目录（文档均为自动生成，因为不要修改）
├── dist                               // 编译之后生成的文件将会在此目录下
├── private                            // 未完成、未发布的文档临时保存在这里，以便让重建全站文档索引的系统任务忽略这些文件
├── templates                          // 文档网站的 HTML 页面模板
├── views                              // Markdown 格式文档的模板文件和源文件，使用时会被编译到 md 目录中
├── CHANGELOG.md                       // changelog 记录
└── ...
```