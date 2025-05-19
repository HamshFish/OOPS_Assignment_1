# Quiz Section

### Question 1: List 3 major version control software for software engineering.
<ol>
    <li> Git <br>
    <li> CVS <br>
    <li> SVN </li>
</ol>

### Question 2: What are the main advantages to using Git in your software development, and how is it useful for game developers?
The advantages of using Git for software development include its optimised performance to be fast and efficient, cross platform compatability and the ability for development teams to work simultaneously on the same project.

### Question 3: Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge.
Branch - a split off version of the overarching repository, which can also be defined as independent lines of development. 

Repository - The main hub where all your files and directories are stored to be cloned onto your computer.

Pull - Obtains updated files to be used as new content for the repository.

Push - The term used to upload updated content from the local repo into a remote repo.

Working Copy - A directory that contains lots of files and a subdirectory.

Merge - Combines changes made from one branch to another, i.e. the Development branch is combined with the main branch on merge.

### Question 4: 4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
Procedures a company will have about using version control systems is to establish a version control system, use naming conventions, regularly commit changes, review the code, branch and merge work, as well as backup and restore files that may be lost during the production of the application.

### Question 5: Merge conflicts can occur while using git. List merge or diff tools you can use to help merge content and deal with conflicts.
<ol>
<li> git checkout <br>
<li> git diff <br>
<li> git status </li>
</ol>

### Question 6: In a merged source code file, how does Git let you know there is a conflict?
Upon merging a branch within a command line application, Git will notify you about a merge conflict in affected files, and using the git command 'cat' <file_name> will show conflict dividers which is: =======, in which any file modifications below the divider will be flagged as conflicting code.

### Question 7: What are the steps you can take to resolve merge conflicts?
<ol>
<li> Open conflicted files and make necessary changes
<li> Use the git add command to stage the edited file for the new merged content
<li> Create a new commit with git commit
</ol>

### Question 8: What does a git revert do and how can it be used?
It can be used as a safe method of change undoing by creating a new commit that inverts specified changes rather than deleting commits from the commit history.

### Question 9: What does a git reset do and how to use it?
Discards following commits after a specified commit and undoes changes in the working directory.

### Question 10: What is the difference between a git revert and reset?
A revert inverts changes done to a commit, while a reset deletes all following commits after a specified commit.

### Question 11: True or False: It is ok to commit broken code to the main branch.
False. All code should be in working order BEFORE you commit them.

### Question 12: True or False: You should commit related changes. For example, fixing 2 unique bugs should produce seperate commits.
True. Bloated commits can be confusing and broken changes may brick the files.

### Question 13: Describe what is DevOps, how is it useful to game developers?
DevOps are tools that can be used by game developers to manage work item tracking, version control and build pipelines, and typically uses cloud storage and computing to improve communication and collaboration between the team.

### Question 14: List what tools can be used with DevOps. Give a brief description of each. (Minimum 3)
<ol>
<li> Git - a distributed version control system that tracks file versions and changes within the source code, allows multiple developers to collaborate on the same project by creating independent branches that can be later merged into the main code and enables offline work.
<li> Microsoft Teams - a collaboration tool that provides chat, meetings and file collab functionalities.
<li> SaltStack - an open source configuration management and automation tool that manages and configures IT infrastructure efficiently, enables admins to run commands ovr multiple machine simultaneously, and offers ease of version control.
</ol>

### Question 15: What is CI/CD and how can it be used to automate the game dev process?
Continuous Delivery and Integration aims to streamline and accelerate the software development lifecycle. Continuous Integration automates integration of code into the build, and Continuous Delivery automate the completion of the process.
