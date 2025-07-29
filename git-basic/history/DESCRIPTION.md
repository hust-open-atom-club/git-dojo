我们已经在 `/tmp/repo` 目录下初始化了一个 Git 仓库。

本关任务较为基础，目标是让你学会如何查看 Git 提交历史，并回退到指定版本。

**背景：**

在一次Git仓库的版本更新中，你不慎将一个重要资料文件answer.txt删除，你需要将版本回退到当时的状态，拿到资料。

**具体任务：**

1. 使用：
      - `git log` 查看提交历史 
      
      - `git diff` 确认文件差异 

2. 找到提交信息为 `"Add correct answer"` 的那一版 

3. 让当前 `HEAD` 指向该提交 

   - 可以 `git checkout <commit>`（会进入 detached HEAD）

   - 也可以 `git reset --hard <commit>`（回滚分支） 

完成后，运行： `/challenge/check` 即可验证并获得本关的 flag！



