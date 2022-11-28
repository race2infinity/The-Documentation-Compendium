# 参与指南

- 参与 The Documentation Compendium 项目很简单，本文档教你快速上手。

## General
- 请参照 [Codebase Structure](./CODEBASE_STRUCTURE.md) 了解本项目的文档结构。
- 请确保你做的每一项更符合本 repo 的 [Coding Guidelines](./CODING_GUIDELINES.md)。
## 提交更改

- Fork the repo
  - <https://github.com/kylelobo/The-Documentation-Compendium/fork>
- Check out a new branch based and name it to what you intend to do:
  - Example:
    ````
    $ git checkout -b BRANCH_NAME
    ````
    If you get an error, you may need to fetch fooBar first by using
    ````
    $ git remote update && git fetch
    ````
  - Use one branch per fix / feature
- Commit 你的更改
  - 请提供 git message 解释你做了什么
  - 请确保你的commit messages 遵循这一[conventions](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53#file-commit-message-guidelines-md)
  - Commit to the forked repository
  - 示例:
    ````
    $ git commit -am 'Add some fooBar'
    ````
- Push to the branch
  - Example:
    ````
    $ git push origin BRANCH_NAME
    ````
- Make a pull request
  - Make sure you send the PR to the <code>fooBar</code> branch
  - Travis CI is watching you!

如果你遵循以上步骤，你的PR将会顺利被合并到main repo 中。

