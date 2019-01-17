# [阿拉贡维基百科 wiki.aragon.org](https://wiki.aragon.org/) <img align="right" src="https://github.com/aragon/design/blob/master/readme-logo.png" height="80px" />

## 本维基百科包含了与阿拉贡项目相关的大多公开内容及资源

如果您有意做出贡献如增改内容、提出错误已经其他反馈，敬请创建[Issues](https://github.com/jiangbubai/aragon-wiki-zh_cn/issues) 并提交[Pull Request](https://github.com/jiangbubai/aragon-wiki-zh_cn/pulls)

## 本百科使用MKDocs作为wiki系统进行创建，相关版本信息如下:
主程序 [MKDocs version 0.17.3](http://www.mkdocs.org/about/release-notes/)

主题 [Material for MkDocs version 2.7.3](https://squidfunk.github.io/mkdocs-material/release-notes/)

### 如需升级MKDocs，执行如下命令:
`pip install --upgrade mkdocs`

`pip install --upgrade mkdocs-material`

## How do I run a local version of the wiki for editing?
## 如何运行一个本地环境来编辑内容？

- 安装 [MkDocs](http://www.mkdocs.org/)
  - 使用Python安装 mkdocs-material主题 `pip install mkdocs-material`
- 克隆Git仓库 `git clone https://github.com/jiangbubai/aragon-wiki-zh_cn.git`
- 进入 `aragon-wiki` 目录，执行 `mkdocs serve` 命令
- 任意浏览器打开 [http://localhost:8000/](http://localhost:8000/) 进行访问

## 如何提交一个新的[Pull Request](https://github.com/jiangbubai/aragon-wiki-zh_cn/pulls)

- 查看[**Issues**](https://github.com/jiangbubai/aragon-wiki-zh_cn/issues) 是都存在相同想法
- 如果未发现有相似或相近的情况，则可以提交[**new Issue**](https://github.com/jiangbubai/aragon-wiki-zh_cn/issues/new) 来描述您的提交。

步骤如下：

- Fork [Aragon Wiki GitHub repository](https://github.com/jiangbubai/aragon-wiki-zh_cn)
- **提交 Pull Request** 后Merge到主仓库

## 部署改动后的维基百科

进入 `aragon-wiki` 目录，执行 `mkdocs gh-deploy` 命令后按提示进行
