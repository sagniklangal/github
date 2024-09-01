# Repo push

1. **Git initialization**:

```bash
git init
   ```
2. **Change branch name**:

```bash
git branch -m main
   ```
3. **Set remote url**:

```bash
git remote set-url origin https://github-token@github.com/username/repo name
   ```
4. **Stage the folders and files**:

```bash
git add .
   ```
4. **Initial commit**:

```bash
git commit -m "Initial commit"
   ```
4. **Initial Push**:

```bash
git push origin main
   ```
4. **Pull**:

```bash
git push origin main
   ```
5. **Pull**:

```bash
git pull origin main --allow-unrelated-histories
   ```
6. **Reconcile divergent branches**

```bash
git pull --rebase origin main --allow-unrelated-histories
   ```
7. **Push**

```bash
git push -u origin main
   ```

# File deletion

1. **Delete the files locally**: You can delete the files directly from your local repository using your file manager or by using the command line.

   For example, to delete a file named `example.txt`, you can use:
   ```bash
   rm example.txt
   ```

2. **Stage the changes**: After deleting the files, stage the changes using the `git add` command. This will mark the deleted files for removal in the next commit.

   ```bash
   git add -u
   ```

   The `-u` option stages changes to tracked files (including deletions).

3. **Commit the changes**: Commit the changes with a descriptive message.

   ```bash
   git commit -m "Removed unnecessary files"
   ```

4. **Push the changes to the remote repository**: Finally, push the changes to your GitHub repository.

   ```bash
   git push origin main
   ```

   Replace `main` with the name of your branch if you are working on a different branch.

This will delete the files from the remote repository as well, reflecting the changes you've made locally.
