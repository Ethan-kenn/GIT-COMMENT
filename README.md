# GIT-COMMENT
HERE THE ALL GIT COMMENTS

-------------------------------

```base
🗂️ File Sections (as seen inside)

A. Setup & Configuration  
B. Repository Initialization & Cloning  
C. Checking Repository Status & Information  
D. Adding, Committing & Managing Changes  
E. Undoing & Restoring Changes  
F. Branching & Merging  
G. Remote Repository (GitHub Connection & Sync)  
H. Stashing (Temporarily Save Work)  
I. Tagging & Releases  
J. File Management & Search  
K. Advanced & Utility Commands  
--------------------------------------
```


HERE THE ALL GITHUB COMMENTS :
--------------------------------
#  HERE THE IMG OF ALL COMMENT'S

<img width="848" height="3280" alt="image" src="https://github.com/user-attachments/assets/cb99aba2-1f27-4657-91d3-a40b5078032c" />

#  Git & GitHub Commands		
		

**A. Setup & Configuration**		
```base
1	git --version	Check the installed Git version.
2	git config --global user.name "Your Name"	Set your Git username globally.
3	git config --global user.email "your.email@example.com"	Set your Git email globally.
4	git config --list	View all Git configuration settings.
5	git config --global core.editor "code --wait"	Set VS Code as the default Git editor.
6	git config credential.helper store	Save credentials for future Git operations.
```

**B. Repository Initialization & Cloning**		
```base
7	git init	Initialize a new Git repository in the current directory.
8	git init --bare	Initialize a bare repository (no working directory).
9	git clone <repository_url>	Copy a remote repository to your local machine.
10	git clone <url>	Clone a remote repository locally.
```

**C. Checking Repository Status & Information**
```base
11	git status	Show the current state of the working directory and staging area.
12	git log	Display a list of all commits in the repository.
13	git log --oneline	Show commit history in one line per commit.
14	git shortlog	Summarize commit history by author.
15	git show <commit_id>	Show details of a specific commit.
16	git describe	Describe the current commit using the most recent tag.
17	git show-branch	Display branches and their commits.
18	git reflog	Show history of HEAD changes and branch movements.
```
**D. Adding, Committing & Managing Changes**
```base
19	git add <file>	Add a file to the staging area.
20	git add .	Add all modified and new files to the staging area.
21	git commit -m "message"	Commit staged changes with a message.
22	git commit -am "message"	Add and commit all tracked files in one command.
23	git diff	Show changes between working directory and staging area.
24	git diff --staged	Show changes between staging area and last commit.
25	git diff --name-only	Show only filenames that changed.
26	git diff <branch1>..<branch2>	Show differences between two branches.
```
**E. Undoing & Restoring Changes**		
```base
27	git reset <file>	Unstage a file without discarding changes.
28	git reset <commit_id>	Move the HEAD to a specific commit (changes stay local).
29	git reset --hard	Discard all local changes and reset to last commit.
30	git reset --hard <commit_id>	Completely reset to a specific commit and remove later changes.
31	git restore <file>	Restore a modified file to the last commit state.
32	git restore --staged <file>	Unstage a file while keeping changes.
33	git revert <commit_id>	Undo a commit by creating a new one that reverses changes.
34	git clean -f	Remove all untracked files from the working directory.
```
**F. Branching & Merging**
```base
35	git branch	List all local branches.
36	git branch <branch_name>	Create a new branch.
37	git branch -d <branch_name>	Delete a local branch.
38	git checkout <branch_name>	Switch to another branch.
39	git checkout -b <branch_name>	Create and switch to a new branch.
40	git merge <branch_name>	Merge a branch into the current branch.
41	git merge --no-ff <branch_name>	Merge branch with a new commit even if fast-forward is possible.
42	git merge --abort	Cancel a merge conflict and return to previous state.
43	git rebase <branch_name>	Apply commits from another branch on top of the current one.
44	git cherry-pick <commit_id>	Apply a specific commit from another branch.
```
**G. Remote Repository (GitHub Connection & Sync)**		
```base
45	git remote	List remote repositories connected to the project.
46	git remote -v	Show remote repository URLs.
47	git remote add origin <url>	Connect local repository to a remote GitHub repository.
48	git remote remove origin	Remove a remote connection.
49	git push origin <branch_name>	Push changes to a specific branch on remote.
50	git push -u origin <branch_name>	Push branch and set it as default upstream.
51	git push	Push committed changes to the remote repository.
52	git push origin --delete <branch_name>	Delete a remote branch.
53	git pull	Fetch and merge changes from the remote repository.
54	git pull origin main	Pull latest changes from the main branch of remote repository.
55	git fetch	Download changes from remote without merging.
56	git push origin --tags	Push all tags to the remote repository.
```
**H. Stashing (Temporarily Save Work)**		
```base
57	git stash	Temporarily save uncommitted changes.
58	git stash list	List all stashed changes.
59	git stash apply	Reapply last stashed changes.
60	git stash pop	Reapply and remove the latest stash.
61	git stash drop	Delete the most recent stash.
```
**I. Tagging & Releases**		
```base
62	git tag	List all tags in the repository.
63	git tag <tag_name>	Create a new tag.
64	git tag -a <tag_name> -m "message"	Create an annotated tag with a message.
```
**J. File Management & Search**		
```base
65	git rm <file>	Remove a file from working directory and staging area.
66	git mv <old> <new>	Rename or move a file.
67	git ls-files	Show all tracked files in the repository.
68	git grep <pattern>	Search for a text pattern in tracked files.
```
**K. Advanced & Utility Commands**
```base
69	git blame <file>	Show who last modified each line in a file.
70	git archive	Create a zip or tar archive of a repository snapshot.
```





