我们已经在 `/tmp/repo` 目录下初始化了一个 Git 仓库。

本关目标是让你学会使用 `git cherry-pick` 将指定提交应用到当前分支。

**背景：**

你在维护一个 Python 项目，当前的 master 分支中缺少关键函数 `run()`，而这个函数已经被另一个开发者在 `feature` 分支中添加了。项目经理要求你只引入该函数，而不是合并整个 `feature` 分支的所有更改。

**具体任务：**

- 进入 `/tmp/repo`，该仓库已经初始化并包含两个分支：`master` 和 `feature`。

- `feature` 分支中包含多个提交，其中有一个添加了 `def run()` 函数到 `app.py`。

- 请使用 `git cherry-pick`，将这个提交合并到 `master` 分支。

- 不要使用 merge 或 rebase 操作！

- 最终，你的 `app.py` 中应包含该函数，并且提交历史保持线性。

**提示：**

- 使用 `git log feature` 查看提交信息。

- 切换到 `master` 分支再执行 `git cherry-pick <commit-hash>`。

- 如果 cherry-pick 出现冲突，解决后继续。

完成后，运行 `/challenge/check` 即可验证并获得本关的 flag！

