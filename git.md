`git config --global user.name "..."`设置用户名

`git config --global user.email "..."`设置用户邮箱

`git init`将目录变成Git可以管理的仓库

- 添加新文件到Git仓库-两步（提交修改和提交新文件一样的操作）

  `git add <file>`可反复多次使用，添加多个文件

  `git commit -m <message>`完成

`git status`查看仓库当前状态

`git diff <file>`查看文件的修改内容

`git log`（--pretty=oneline可使一行显示一天历史提交）查看提交历史，以遍确定要回退到哪个版本

`git reset --hard commit_id` 在版本的历史之间穿梭 `HEAD`指向当前版本，commit_id可以是`HEAD^`-上个版本，`HEAD^^`上上个版本，或者直接是版本的ID

`git reflog` 查看命令历史，以便确定要回到未来的哪个版本

