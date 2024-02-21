# Code Versioning Workshop Homework

Git was created by Linus (creator of Linux), Git is a version control system that helps developers to create and modify their programs.

**Common command in Git**
1. $ git init -> Initialize git
2. $ git add ‘file-name’ -> Staging the filename
3. $ git commit -> Committing
4. $ git log -> check git log
5. $ git reset —soft reset -> with preserved file
6. $ git reset —hard reset -> with no preserved file
7. $ git diff -> to compare

**Branching and Merging**
Branching is a method where Git creates a copy of the main program that can be used as an experiment that will not affect the main program.

Merging is a method where combining 2 branch into 1 branch.

Common command line for Branching and Merging
1. $ git branch -> to create branch
2. $ git checkout -b ‘filename’ -> to create and switch branch
3. $ git branch -d ‘filename’ -> to delete branch
4. $ git checkout main; $ git merge ‘filename’ -> to merge branch

**Remote Repository**
Remote repository is a repository that are hosted by another server (ex: GitHub), and it helps developer to access the same file.

Common command line for Remote Repository
1. Git clone -> Copy the repository to local
2. Git fetch -> Tidak apply semua perubahan
3. Git Pull (Git Fetch + Merge) -> Apply semua perubahan

**Identification and Verification**
People can impersonate another people to do bad things to your code, GitHub recognize this problems and there is a solution called Commit Signing. It helps to verify the identity of a person so that all commit, request, etc, can be monitored perfectly.

**Conclusion**
Git and Github really helpful for developers to create, modify, and maintain their programs.
