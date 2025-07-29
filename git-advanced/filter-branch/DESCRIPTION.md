我们已经在 `/tmp/repo` 目录下初始化了一个 Git 仓库。

本关目标是让你学会清除git的历史记录

**背景：**

在 `/tmp/repo` 中，我们已经帮你初始化好了一个 Git 仓库，但不小心提交了含有敏感信息的 `passwords.txt` 文件。

**具体任务：**

将 `passwords.txt` 从所有提交中彻底移除，让 Git 仓库的提交历史里不再包含这个文件。

**提示：** 

可以使用 `git-filter-repo` 清理 git 历史记录。

完成后，运行： `/challenge/check` 即可验证并获得本关的 flag！
