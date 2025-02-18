# Rustlang-cn [![Build Status](https://dev.azure.com/rustlang-cn/rustlang-cn/_apis/build/status/rustlang-cn.rustlang-cn?branchName=master)](https://dev.azure.com/rustlang-cn/rustlang-cn/_build/latest?definitionId=1&branchName=master) [![matrix](https://about.riot.im/images/favicon-32.png)](https://riot.im/app/#/room/#rustlang-cn:matrix.org)

## 一、参与 Rust 中文阅读投稿

> [欢迎加入](https://github.com/rustlang-cn/Important/issues/1)Rust中文,共建Rust语言中文网络！欢迎向[Rust中文阅读](https://rustlang-cn.org/read/)投稿,好文将展示在以下Rust中文网络点：

- [Rust中文阅读](https://rustlang-cn.org/read/)
- [Rust中文论坛](http://ouisrc.xyz/a/community/rust)
- [Rust中文聊天室](https://riot.im/app/#/room/#rustlang-cn:matrix.org)
- [Rust中文知乎](https://zhuanlan.zhihu.com/rustlang-cn)
- [Rust中文微博](https://weibo.com/kriry?is_all=1)
- **Rust中文QQ群:570065685**

**说明**：文章投稿可以直接PR本仓库，也可以投递文章链接（请选用易使用的格式，如：Markdown）。本专栏默认 MIT 协议，如你的文章有其他要求可注明。

## 二、参与 Rust 中文网站建设

> 因为本仓库的修改会自动发布到 [rustlang-cn](https://rustlang-cn.org/) 网站，请参与时遵循以下步骤，并确保构建为成功状态。

### A. 参与文档

**如果你只想修改文件，不用操作下面添加文件的步骤，你可以修改 `docs` 目录内的任何 `.md` 文件。**

### B. 参与网站

**如果你想添加更多文件或改变主题结构布局，请遵循以下步骤。**

1. Fork 并克隆本仓库：

    ```bash
    $ git clone https://github.com/<YOUR_GITHUB_ID>/rustlang-cn
    $ cd rustlang-cn
    $ npm install
    ```

2. 测试，可以在终端查看测试输出：

    ```bash
    $ npm run dev
    ```

    打开浏览器 <http://localhost:8080> 查看页面效果。

3. 修改/添加 `docs` 目录内的文件, 保证步骤二测试运行没有错误。

4. Push 到你的 GitHub 仓库，然后提交 PR 到本仓库。
