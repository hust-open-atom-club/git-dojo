我们已经在 `/tmp/repo` 目录下初始化了一个 Git 仓库。

本关目标是让你学会使用 `git rebase` 实现线性提交历史的合并。

**背景：**

你是某团队的开发成员。大家最近在 `feature` 分支上完成了一项重要的新功能开发。现在，项目经理要求将 `feature` 分支上的更改合并回主分支 `master`，但有一个关键要求：提交历史必须保持线性，不能出现 merge commit！

**具体任务：**

* 进入 `/tmp/repo` 目录，仓库已经初始化，包含 `master` 和 `feature` 两个分支。

* 将 `feature` 分支上的提交整合进 `master` 分支中：

  * 必须保留每一次提交的信息（不能 squash）。

  * 提交历史必须线性（不能出现合并节点）。

* 最终你应处于 `master` 分支，并且该分支应包含原 `feature` 分支上的所有更改。

**提示：**

* 使用 `git rebase` 来整合分支内容；

* 使用 `git log --oneline` 查看提交历史；

* 使用 `git log --merges` 检查是否有合并提交；

* 注意提交顺序与完整性；

* 可用 `git diff master feature` 理解两个分支差异。

完成后，运行： `/challenge/check` 即可验证并获得本关的 flag！

