#Get/Github Notes

Note:use ctrl+shift+v to preview md files in VS Code

## Basic Concepts

1. **Repsitory (repo)**
   A project folder that Git is tracking. Can be **local** (on your computer) or **remotes** (Like GitHub)

2. **Version Control**
   A system that tracks changes to code over time,letting you revert to previous verisons or collaborate with others

3. **Commit**
   A snapshot of your changes. Includes a message descibing what was changed.

4. **Working Directory**
   the current state of your file on disk.

5. **Staging Area**
   Where you prepare changes before committing. You "stage" files that are ready to be committed.

---

6. `git init`
   Initializes a new Git reposiory in a folder.

7. `git status`
   Shows the current state of the working directory and staging area.

8. `git add <file>`
   Stages changes in a file for the next commit. (note you can `git add *` to stage all files in the working directory, while `git add .` does the whole repository)

9. `git commit -m "message"`
   Saves the staged changes with a commit message

10. **Add a remote location for a repo**

```
git remote add origin <link to repo>
git branch -M main
git push -u origin main
```

11. `git push`
    Sends local commit to the remote repository.

12. `git pull`
    Fetches **and merges** changes from the remote repository to your local one.

13. `git fetch`
    Downloads changes from remote, but doesnt merge them automaticaly

14. `git merge`
    merges changes from one branch into another.

15. `git branch <branch_name>`
    Create a new branch

16. `git checkout "branch name"`
    Switch to a different branch (edits/commits will be on this now)
