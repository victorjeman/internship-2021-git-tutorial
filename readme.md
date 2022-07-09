<h1 align="center" style="display: block; font-size: 2.5em; font-weight: bold; margin-block-start: 1em; margin-block-end: 1em;">

<a name="logo" href="https://victorjeman.com">
  <img align="center" src="/assets/git-workshop.png" alt="GIT Workshop" style="width:100%;height:100%"/>
</a>

# Git Workshop

> Let's learn the basics about git together.

<br/><br/><br/>

## What is vesion control?[![](/assets/pin.svg)](#what-is-version-control)

<p align="center">
  <img width="800" src="/assets/version-control.png">
</p>

<br/>
  
> 💡 Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control software keeps        track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

<br/>

[What is version control? | atlassian tutorial](https://www.atlassian.com/git/tutorials/what-is-version-control)

---

<br/><br/><br/>

## Version control tool(s)?[![](/assets/pin.svg)](#version-control-tools)

<br/>

<p align="center">
  <img width="500" src="/assets/there-can-be-only-one.jpg">
</p>

<br/>

<p align="center">
  <img width="500" src="/assets/wrong.gif">
</p>
  
<br/>

> 💡 There are a lot of these.

<br/>

<p align="center">
  <img style="width:100%;height:100%" src="/assets/version-control-tools.jpg">
</p>

<br/>

[15 BEST Version Control Software (Source Code Management Tools)](https://www.softwaretestinghelp.com/version-control-software)
  
---

<br/><br/><br/>

## What is git?[![](/assets/pin.svg)](#what-is-git)
<br/>

<p align="center">
  <img style="width:100%;height:100%" src="/assets/git.jpg">
</p>

<br/>

  > 💡 Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

<br/>

<p align="center">
  <img width="800" src="/assets/why-are-my-changes-gone.png">
</p>

<br/>
  
* [What is git? | git website](https://git-scm.com)
* [git github repo](https://github.com/git/git)

---

<br/><br/><br/>

## Git based platforms[![](/assets/pin.svg)](#git-based-platforms)

<br/>

<p align="center">
  <img width="700" src="/assets/git-based-fully-integrated-platform.jpg">
</p>

<br/>

> 💡 There are multiple cloud platforms that are working based on git.

<br/>

* [github](https://github.com)
* [gitlab](https://about.gitlab.com)
* [bitbucket](https://bitbucket.org)
  
---

<br/><br/><br/>

-----
# Separator
-----

* [What is git?](https://github.com/git/git)

* Version control tools

* [Git-based fully integrated platform for software development]
* ![git-based-fully-integrated-platform](/assets/git-based-fully-integrated-platform.jpg)

* ![where are my change](https://preview.redd.it/p2fa7cnx1pz31.png?auto=webp&s=48bd912260742bc2f743a11d227c06489973cf3e)

* Why git?

* Create a [GitHub account](https://github.com)

* Download [Git bash](https://git-scm.com/downloads)


* Create a ssh key

  * Enter `ls -al ~/.ssh` to [see if existing SSH keys are present](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/checking-for-existing-ssh-keys)

  * [Generating a new SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

  * [Add ssh key to your GitHub Profile](https://github.com/settings/ssh/new)


## Git basic flow. Createa a [new repository](https://github.com/new)
  
  * Create new repo 
  * ![new repo](/assets/new-repo.jpg)

  * Add repo details
  * ![new repo form](/assets/new-repo-form.jpg)

  * Clone the repo
  * ![clone repo](/assets/clone-info.jpg)
  * ![clone repo](/assets/clone-repo.jpg)

  * cd into the project
  * ![clone repo](/assets/cd-project.jpg)

  * Create *.gitignore* file and a **ignore-me.md** file
  * Add **ignore-me.md** file ot the **.gitignore**
  * ![clone repo](/assets/ignore-a-file.jpg)

  * Push the changes to remote branch
  * ![clone repo](/assets/push-changes.jpg)


  * See that **.gitignore** file has been added into the main branch
  * ![clone repo](/assets/gitignore-created.jpg)

  * ![git commit](https://preview.redd.it/8mcssb978dk51.png?width=960&crop=smart&auto=webp&s=c633b0ac2896bb180e5c4e6c701f04326e6a1375)


## Create a Pull Request

  * Create a new branch, `git checkout -b YourName`, e.g. `git checkout -b VictorJeman`
  * ![clone repo](/assets/create-new-branch.jpg)

  * Add a new file **YourName.md** and write something in it.
  * ![clone repo](/assets/add-a-file.jpg)

  * Add all your changes to git 
  * `git add .`
  * `git commit -m "Created a file with my name and did some changes in it"`
  * `git push origin VictorJeman`
  * ![clone repo](/assets/push-the-changes.jpg)
  

  * Create a Pull Request from your **YourName** branch into **main** branch
  * ![clone repo](/assets/create-pull-request.jpg)
  * or
  * ![clone repo](/assets/create-pull-request-2.jpg)


  * Select merge type
  * ![clone repo](/assets/select-merge-type.jpg)
  * ![clone repo](/assets/squash-and-merge.jpg)

  * Merge Pull Requests into **main** branch and delete the temporary branch
  * ![clone repo](/assets/delete-branch-after-merge.jpg)

  * ![git pull rquest](https://pics.me.me/just-make-sure-they-merge-my-pull-request-imgflip-com-programmer-29564995.png)


## Solving conflicts

  * TODO: To add pictures


## Extra

  * [GitHub Desktop](https://desktop.github.com)

  * [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

