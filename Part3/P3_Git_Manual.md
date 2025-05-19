# Installing Git
<ol>
<li> Head to https://gitforwindows.org/ to download the latest version of Git. NOTE: Windows computers are required to be 8.1 or later on i686 and x86_64 CPU architectures. 
<li> Follow instructions as provided by Git Setup until the installation is complete.
<li> Open the command prompt, or Git Bash if you selected not to use the standard way during installation.
<li> Type 'git version' to verify that Git installed correctly. <br>
<br>If you had issues installing Git, contact your workplace IT professional and ask about what to do next.
</ol>

# Learning Git
### Principles and techniques for creating and working with repositories:
<ol>
<li> Create a README file - README's are files that give a general overview of what the repository is about and clarifies navigation about your work.
<li> Secure your repository - Setting up security measures ensures that your repository is protected from unauthorised access, secrets like API keys and tokens and prevents vulnerable code is not exploited by mal-actors.
<li> Use .gitignore - .gitignore removes all unecessary files that end up making the clone and download process longer as the computer has to download other files that are included from the repo origin like Unity. </li>
</ol>

### Principles and techniques for creating and working with branches:
<ol>
<li> Create focused and compact branches - focusing on specified tasks can help streamline and track changes in the code and creates clarity of the task taken.
<li> Use meaningful naming conventions - Meaningful names for branches can help others understand what the branches purpose is and allows teammates to be informed of actions taken.
<li> Following a Git Workflow - Git workflows allows for all members of the development team to make changes at an efficient rate without conflicting changes between eachother and can be used to fix small bugs away from the main branch. </li>
</ol>

# Recommended Git workflow
<ol>
<li> Create a development branch from the main branch.
<li> Create a release branch and X amount of feature branches from the development branch.
<li> Merge completed feature branch(s) into the development branch.
<li> Merge finished release branch into the development branch and again into the main branch.
