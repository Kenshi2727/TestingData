git show <commit-hash>:index.js
//for accessing version of files based on commit-hash

//info---->

The `-M` flag in the `git branch -M` command stands for **"move or rename"**. It is used to rename the current branch to a new name, and if a branch with the target name already exists, it will forcefully overwrite it.

For example:
```bash
git branch -M main
```

- Renames the current branch to `main`.
- If a branch named `main` already exists, it will **overwrite** it.

This is particularly useful when you are transitioning from using `master` to `main` as the default branch, or when you want to standardize branch names. 

### Key Difference:
- `-m`: Renames the branch but throws an error if the target branch already exists.
- `-M`: Renames the branch and **overwrites** an existing branch with the same name.
