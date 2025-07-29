我们已经在 `/tmp/repo` 目录下初始化了一个 Git 仓库。

本关目标是让你学会使用 `git rebase`、`git reset` 等 Git 命令，将原本凌乱的提交整合为**更简洁、易读的提交历史**。

**具体任务：**

在 `/tmp/repo` 中，我们已经帮你初始化好了一个 Git 仓库，并准备了共 4 个提交：

- initial commit

- add part1

- add part2

- add part3

你需要将最后的 3 个提交（add part1、add part2、add part3）**合并成 1 个提交**，合并后最终只保留 2 条提交记录：

- initial commit

- 一个新的提交，包含 part1.txt、part2.txt、part3.txt 三个文件

完成后，运行： `/challenge/check` 即可验证并获得本关的 flag！

