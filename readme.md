# ASSIST Internship 2021 

## Git Basics

* What is git?

* Why git?

* Create a  [GitHub account](https://github.com)

* Download [Git bash](https://git-scm.com/downloads)

* Create a ssh key

  * Enter `ls -al ~/.ssh` to [see if existing SSH keys are present](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/checking-for-existing-ssh-keys)

  * [Generating a new SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

  * [Add ssh key to your GitHub Profile](https://github.com/settings/ssh/new)

* Create a [new repository](https://github.com/new)
  
  * Name it *git-tutorial*

  * Connect the repo to your local machine

  * Create a local branch, `git checkout -b main`

  * Add a file, *readme.md*

  * Write something in *readme.md*, e.g. "Git Tutorial"

  * Create *ignore-me.md* file

  * Add *ignore-me.md* to *.gitignore*

  * Add a single file to git , `git add readme.md`
  
  * Check the files, `git status`

  * Commit your changes, `git commit -m "Added readme file"`

  * Push your changes from your *local main branch* to your *remote main branch*, `git push origin main`
  

* Clone [internship-2021-git-tutorial](https://github.com/victorjeman/internship-2021-git-tutorial)

* Create a new branch

  * `git checkout -b VictorJeman`

  * `Add a new file YourName.md`

  * Copy the content from `happy.md` and make some changes in there

  * Add all your changes to git `git add .`

  * Commit your changes, `git commit -m "Created a file with my name and did some changes in it"`

  * Push your changes to your own branch `git push origin YourName`

  * Create a Pull Request from your branch into `main`

  * Pull Request review


* Solving conflicts

  * Change the first line from `happy.md`

  * Push the changes to your remote personal branch

  * I will make some changes in `happy.md`

  * Pull from master and fix the conflicts



* Install [Github Desktop](https://desktop.github.com)


* Extra
  * (markdownguide)[https://www.markdownguide.org/cheat-sheet]