**Git & GitHub - Comprehensive Study Notes for
Data Engineers**

**1. What is Git?**
• Git is an open-source version control system that tracks changes in code.
• It allows creating commits (snapshots), reverting to older versions, and collaborating safely.

**2. What is GitHub?**
• GitHub is a cloud platform that hosts Git repositories.
• It enables collaboration, pull requests, code reviews, and remote backups.

**3. Basic Workflow**
• Working Directory - Where files are edited.
• Staging Area - Temporary area to prepare changes.
• Repository - Stores committed snapshots permanently.

**4. File States**
• Untracked - New files not yet tracked.
• Modified - File changed but not staged.
• Staged - Ready to commit.
• Committed - Snapshot saved in repository.

**5. Essential Commands**
• git init - Initialize repository.
• git status - Check file states.
• git add . - Add files to staging.
• git commit -m 'message' - Commit changes.
• git log --oneline - View commit history.
• git diff - View changes.

**6. Branching & Merging**
• git branch - List branches.
• git switch - Switch branches.
• git switch -c branch-name - Create and switch.
• git merge branch-name - Merge branches.
• Resolve conflicts manually if they occur.

**7. Advanced Concepts**
• .gitignore - Ignore sensitive or unnecessary files.
• git rebase - Create clean linear history.
• git cherry-pick - Apply specific commit to another branch.
• git stash - Temporarily save uncommitted work.
• git reflog & git reset --hard - Time travel and restore.

**8. GitHub Integration**
• git remote add origin URL - Connect to remote.
• git push origin main - Push code to GitHub.
• git pull origin main - Pull updates.
• git clone URL - Download repository.

**9. Importance for Data Engineers**
• Manage ETL pipelines effectively.
• Enable collaboration across teams.
• Handle production hotfixes safely.
• Prevent sensitive data leaks.
• git pull origin main - Pull updates.
• git clone URL - Download repository.
