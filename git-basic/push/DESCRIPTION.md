我们已经在 `/tmp/repo` 目录下初始化了一个 Git 仓库。

本关任务较为基础，目标是把当前 `master` 分支推送到指定远程仓库，并让本地 `master` 跟踪 `origin/master`。

在关卡初始化中已经完成了repo仓库的`git add`和`git commit`操作。

**具体任务：**

1. 查找并添加远程仓库（命名为origin）。

2. 推送当前分支到远程

**提示：**

- 远程仓库是本机路径，添加方式与 `file:///…` 或绝对路径相同。  

- 成功推送后，本地 `master` 应显示上游：  

  ```bash
  On branch master, your branch is up to date with 'origin/master'.
  ```
  
完成后，运行： `/challenge/check` 即可验证并获得本关的 flag！