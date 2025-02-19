1. **查看文件状态：** 使用 `git status` 查看哪些文件被修改或新增。

   ```bash
   git status
   ```

2. **添加文件到暂存区：** 如果有修改的文件，使用 `git add` 命令将修改的文件添加到暂存区。例如：

   ```bash
   git add myfile.cpp
   ```

   如果想添加所有修改过的文件，可以使用：

   ```bash
   git add .
   ```

3. **提交修改：** 使用 `git commit` 命令提交更改，并附上合适的提交信息。例如：

   ```bash
   git commit -m "Updated cpp files"
   ```

4. **推送到远程仓库：** 使用 `git push` 将本地的提交推送到远程仓库：

   ```bash
   git push origin master
   ```

   这里 `origin` 是远程仓库的名称，`master` 是你要推送的分支名。如果是 `main` 分支，可以使用：

   ```bash
   git push origin main
   ```

