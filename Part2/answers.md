**1.List three major version control software for software engineering.**
   - Git
   - Subversion (SVN)
   - Mercurial
**2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.**
   - Distributed version control system
   - Strong support for non-linear development
   - Strong comunity support
**3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge**
   - **Branch:** a parallel version of the MAIN branch
   - **Pull:** Fetching changes and merging them to different repositories
   - **Push:** Sending changes to a remote repository.
   - **Repository:** storage for your project, including its history.
   - **Working Copy:** The copy of files where edits are made.
   - **Merge:** Combining changes from different branches or forks.
**4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.**
   - policies on branching strategies
   - procedures for code reveiws and pull request workflows.
   - guidelines for handling sensitive information in repositories.
**5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.**
   - Diff tools: Beyond Compare, KDiff3, Meld
   - Merge tools: TortoiseMerge, Araxis Merge, P4Merge
**6.	In a merged source code file, how does Git let you know there is a conflict?**
   -  Git inserts conflict markers <<<<<<<, =======, >>>>>>> into the file where conflicts exist.
**7.	What are the steps you can take to resolve Git conflicts?**
   - Identify conflicting files using git status or merge tool.
   - Edit conflicted files to resolve differences manually.
   - Stage resolved files with git add and commit changes.
**8.	What does git revert do, and how can you use it?**
   - git revert undoes a commit by making a new one
**9.	What does git reset do, and how can you use it? **
   - git reset move the head and branch pointer to a new commit
**10.	What is the difference between git revert and git reset?**
   - git revet create a new git
   - git reset moves the current branch pointer
**11.	True or False: It is okay to commit broken code to the main branch.**
   - false
**12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.**
   - true 
**13.	Describe what is DevOps, how is it useful for game developers?**
   - devops is the intergration of development and operation teams to automate software deliveries dev ops facilitate continuous intergration, deployment, and monitoring of games
**14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)**
   - Jenkins Automation server for building, testing, and deploying software.
   - Docker Containerization platform for packaging applications and their dependencies.
   - Ansible Configuration management tool for automating application deployment and system configuration.
**15.	What is CI/CD and how can it be used to automate the game development process?**
	- ontinuous Integration and Continuous Deployment.
	- automates the process of integrating code changes, running tests, and deploying builds.
	- For game development, CI/CD ensures frequent updates, stable builds, and quicker iteration cycles.

### [Back to README](README.md)
