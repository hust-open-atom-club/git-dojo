本关任务非常基础，目标是让你学会如何创建一个新的 Git 仓库，并完成一次简单的提交。

**具体任务：**

1. 在 `/tmp/repo` 目录下使用 `git init` 初始化一个 Git 仓库。

2. 配置 Git 用户信息，例如：

   ```bash
   git config user.name "pwnuser"
   git config user.email "pwn@hust.edu.cn"
   ```

3. 新建一个名为 `hello.txt` 的文件，内容随意填写。

4. 使用 `git add` 将该文件加入暂存区。

5. 使用 `git commit` 提交该文件，提交信息可以自由发挥。

完成后，运行： `/challenge/check` 即可验证并获得本关的 flag！
