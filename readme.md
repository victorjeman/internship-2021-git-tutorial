# ASSIST Internship 2021 

## Git Basics

* What is git?

* ![where are my change](https://preview.redd.it/p2fa7cnx1pz31.png?auto=webp&s=48bd912260742bc2f743a11d227c06489973cf3e)

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

  * ![git branch](https://i.imgflip.com/4ooord.jpg)

  * Add a file, *readme.md*

  * Write something in *readme.md*, e.g. "Git Tutorial"

  * Create *ignore-me.md* file

  * Add *ignore-me.md* to *.gitignore*

  * Add a single file to git , `git add readme.md`
  
  * Check the files, `git status`

  * Commit your changes, `git commit -m "Added readme file"`

  * ![git commit](https://preview.redd.it/8mcssb978dk51.png?width=960&crop=smart&auto=webp&s=c633b0ac2896bb180e5c4e6c701f04326e6a1375)

  * Push your changes from your *local main branch* to your *remote main branch*, `git push origin main`

* Clone [internship-2021-git-tutorial](https://github.com/victorjeman/internship-2021-git-tutorial)

* Create a new branch

  * `git checkout -b VictorJeman`

  * `Add a new file YourName.md`

  * Copy the content from `happy.md` and make some changes in there

  * Add all your changes to git `git add .`

  * Commit your changes, `git commit -m "Created a file with my name and did some changes in it"`

  * Push your changes to your own branch `git push origin YourName`

  * Create a Pull Request from your `YourName` branch into `main` branch

  * Pull Request review

  * Merge Pull Requests in main (me)

  * ![git pull rquest](https://pics.me.me/just-make-sure-they-merge-my-pull-request-imgflip-com-programmer-29564995.png)

* Solving conflicts

  * Change the first line from `happy.md`

  * Push the changes to your remote personal branch

  * I will make some changes in `happy.md`

  * Pull from master and fix the conflicts

  * ![git commit](https://blog.axosoft.com/wp-content/uploads/2019/04/i-love-merge-conflicts.jpg)

* Install [Github Desktop](https://desktop.github.com)

* Extra
  * (markdownguide)[https://www.markdownguide.org/cheat-sheet]