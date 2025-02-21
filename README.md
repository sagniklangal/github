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
git remote add origin https://github.com/sagniklangal/javascript.git
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

# Adding new folder

1. **Stage the new folder**:

```bash
git add "if statements"
   ```
2. **If you want to stage all changes (including the new folder and any other modifications):**:

```bash
git add .
   ```
3. **Commit the changes**:

```bash
git commit -m "Added if statements folder with new code"
   ```
4. **Push the changes to the remote repository**:

```bash
git push origin main
   ```

# Folder entering

### 1️⃣ Using Quotes:
```bash
cd "Web development"
```

### 2️⃣ Using Escape Character (`\` before space):
```bash
cd Web\ development
```

### 3️⃣ If the Folder is Inside Another Directory:
If the folder is inside another directory, specify the full or relative path:
```bash
cd ~/Documents/"Web development"
```
or
```bash
cd ~/Documents/Web\ development
```

### 4️⃣ Using Tab Completion:
Type `cd Web` and press **Tab**, and it will auto-complete the name.

To check if you've entered the folder, use:
```bash
pwd
```
or list files inside:
```bash
ls
```

# Cloning a repository

```bash
git clone repo link folder name/
   ```

# Tracking a remote repository

### 1️⃣ Knowing status:
```bash
git status
```

### 2️⃣ Tracking changes
```bash
git diff
```

# Checking history

### Checking commits(Press enter for loading more commits):

```bash
git log
   ```
### Checking last particular commits:

```bash
git log -3
   ```
### Checking last commits with changes(diff):

```bash
git log -p
   ```
