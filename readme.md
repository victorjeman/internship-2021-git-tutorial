<h1 align="center" style="display: block; font-size: 2.5em; font-weight: bold; margin-block-start: 1em; margin-block-end: 1em;">

<a name="logo" href="https://victorjeman.com">
  <img align="center" src="/assets/git-workshop.png" alt="GIT Workshop" style="width:100%;height:100%"/>
</a>

# Git Workshop

<br/>

> Let's learn the basics about git together.

<br/><br/>

## What is vesion control?[![](/assets/pin.svg)](#what-is-version-control)

<br/>

> 🤔 Question: What is vesion control?
<p align="center">
  <img style="width:100%;" src="/assets/what-is-version-control.jpg">
</p>

<br/>

> 🤔 Question: When you first started to use a version control?
<p align="center">
  <img width="1000" src="/assets/first-time.gif">
</p>

<br/>

> 🤔 Question: What benefits it gave you?
<p align="center">
  <img style="width:100%;height:100%" src="/assets/benefits.jpg">
</p>

<br/>

> 🤔 Question: Does it make sense to use a version control in your personal projects?
<p align="center">
  <img width="1000" src="/assets/it-make-sense.gif">
</p>

<br/>

> 💡 **Version control**, also known as source control, is the **practice** of **tracking** and **managing changes** to software code.  

> 💡 If a mistake is made, developers can turn back the clock and **compare earlier versions** of the code to help **fix the mistake** while **minimizing disruption** to all team members.

<br/>

[What is version control? | atlassian tutorial](https://www.atlassian.com/git/tutorials/what-is-version-control)

---

## Version control system?[![](/assets/pin.svg)](#version-control-systems)

<br/>

> 🤔 Question: What is a version control system?
<p align="center">
  <img style="width:80%;" src="/assets/version-control.png">
</p>

<br/>

> 🤔 Question: How many version control systems do you know?
<p align="center">
  <img width="600" src="/assets/there-can-be-only-one.jpg">
</p>

<br/>

<p align="center">
  <img width="600" src="/assets/wrong.gif">
</p>

<br/>

> 💡 There are a lot of version control systems.
<p align="center">
  <img width="1000" src="/assets/so-many.gif">
</p>

[List of version-control software](https://en.wikipedia.org/wiki/List_of_version-control_software)

<br/>

> 💡 Some of the cool ones! 
<p align="center">
  <img style="width:100%;height:100%" src="/assets/version-control-tools.jpg">
</p>

<br/>

> 💡 Version control systems are **software tools** that help software teams **manage changes to source code over time**.

> 💡 Version control software **keeps track of every modification** to the code in a **special kind of database**.

<br/>

[15 BEST Version Control Software (Source Code Management Tools)](https://www.softwaretestinghelp.com/version-control-software)

<br/>

> 🤔 Question: Version control systems: distributed vs centralized. What is the difference? 
<p align="center">
  <img style="width:100%;height:100%" src="/assets/central-decentral.png">
</p>

<br/>

> 💡 **Centralized** VCSs **keep the history of changes on a central server** from which everyone requests the latest version of the work and pushes the latest changes to. This means that **everyone* sharing the server** also **shares everyone’s work**.

> 💡 On a **Distributed** VCS, everyone has a **local copy of the entire work’s history**. This means that it **is not necessary to be online to change revisions** or add changes to the work.

* **Distributed VCS**: Git, Mercurial.
* **Centralized VCS**: CVS, Perforce, SVN.

<br/>

* [VERSION CONTROL SYSTEMS: DISTRIBUTED VS. CENTRALIZED](https://www.oshyn.com/blog/version-control-systems-distributed-vs-centralized)


---

<br/>

## What is git?[![](/assets/pin.svg)](#what-is-git)
<br/>

<p align="center">
  <img style="width:100%;height:100%" src="/assets/git.jpg">
</p>

<br/>

<p align="center">
  <img width="1000" src="/assets/why-are-my-changes-gone.png">
</p>

<br/>

> 💡 Git is a specific open-source version control system created by Linus Torvalds in 2005 designed to handle projects with speed and efficiency.

<br/>
  
* [What is git? | git website](https://git-scm.com)
* [git github repo](https://github.com/git/git)

---

<br/>

## Git based platforms[![](/assets/pin.svg)](#git-based-platforms)

<br/>

<p align="center">
  <img width="700" src="/assets/git-based-fully-integrated-platform.jpg">
</p>

<br/>

> 💡 There are multiple cloud platforms that are working based on git.

<br/>

* [bitbucket](https://bitbucket.org)
* [github](https://github.com)
* [gitlab](https://about.gitlab.com)
  
---

<br/>

  ## What is GitHub[![](/assets/pin.svg)](#what-is-github)

<br/>

<p align="center">
  <img width="700" src="/assets/github.png">
</p>

<br/>

> 💡 GitHub is a for-profit company that offers a cloud-based Git repository hosting service. Essentially, it makes it a lot easier for individuals and teams to use Git for version control and collaboration.

<br/>

 <p align="center">
  <img width="700" src="/assets/git-is-not-github.png">
</p>
  
* [What is GitHub?](https://kinsta.com/knowledgebase/what-is-github/)
* [GitHub is not git](https://thebittheories.com/the-git-github-conundrum-664555988cf6)
  
---

<br/>

# Playground
  
## STEP 1. Create a GitHub account

<br/>

Create a [GitHub account](https://github.com)
  
---
  
## STEP 2. Get Git bash

<br/>

Download [Git bash](https://git-scm.com/downloads)
 
---  
  
## STEP 3. Get Git bash

<br/>

* Create a ssh key

* Enter `ls -al ~/.ssh` to [see if existing SSH keys are present](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/checking-for-existing-ssh-keys)

* [Generating a new SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

* [Add ssh key to your GitHub Profile](https://github.com/settings/ssh/new)
  
---
  
  

## TASK 1

> 👉 Fa clone la proiect.
```
git clone git@github.com:victorjeman/internship-2021-git-tutorial.git
```

<br/>

> 👉 Verifica branch-ul local pe care te afli. Ar trebuie sa fie branch-ul "main".
```
git branch
```

<br/>

> 👉 Fa un branch nou si da-i numele "feature/task-1".
```
git checkout -b feature/task-1
```

<br/>

> 👉 Cu un "git branch" poti sa confirmi ca te afli pe noul branch creat local.
```
git branch
```

<br/>

<p align="center">
  <img width="700" src="/assets/tasks/2.jpg">
</p>

<p align="center">
  <img width="700" src="/assets/tasks/3.jpg">
</p>

<br/>

> 👉 Creeaza 3 fisiere noi.
```
touch play/pretty-1.md play/pretty-2.md play/pretty-3.md play/pretty-4.md
```

<br/>

> 👉 Scrie in fiecare fisier urmatorul text.
```
I feel charming
Oh so charming
It's alarming how charming I feel
And so pretty
That I hardly can believe I'm real
```

<br/>

> 👉 Verifica situatia.
```
git status
```

<br/>

> 👉 Asa ceva ar trebui sa vezi

<p align="center">
  <img width="700" src="/assets/tasks/1.jpg">
</p>

<br/>

> 👉 Adauga fisierele "pretty-1.md" si "pretty-2.md" in gitul tau local.
```
git add play/pretty-1.md play/pretty-2.md
```

<br/>

> 👉 Verifica situatia. Trebuie sa ai 2 fisiere cu verde si 2 cu rosu. Fisierele cu verde sunt in staged area.
```
git status
```

<br/>
  
> 👉 Adauga un commit cu mesaj si descriere pentru fisierele tale din staged area.
```
git commit -m "TASK 1 | Am adaugat fisierele pretty-1.md si pretty-2.md" -m "So far so good. Primul task nu pare asa de greu."
```

<br/>

> 👉 Fa push cu modificarile din git-ul tau local(staged area) pe remote(GitHub).
```
git push origin feature/task-1
```

<br/>

> 👉 Fa un pull request in GitHub.

<br/>

> 👉 Fa merge la pull request in branch-ul "main".

<br/>

## TASK 2

> 👉 Verifica pe ce branch esti pe local.
```
git branch 
```

<br/>

> 👉 Inainte sa te apuci de un alt task/feature mereu sa mergi inapoi pe branch-ul local "main".
```
git checkout main 
```

<br/>

> 👉 Sterge branch-ul local "feature/task-1". Dupa ce faci merge la un branch in main, mereu sa-l stergi de pe local.
```
git branch -D feature/task-1
```

<br/>

> 👉 Daca nu ai sters branch-ul remote(din GitHub) "feature/task-1" cand ai facut merge in "main", sterge-l acum. Mereu sa stergi branch-urile remote dupa ce le faci merge in branch-ul "main".
```
git push -d origin feature/task-1
```

<br/>

> 👉 Mai verifica o data lista de branch-uri locale. Observa ca branch-ul "feature/task-1 " nu mai apare in lista.
```
git branch
```

<br/>

> 👉 Inainte sa lucrezi la un nou feature, asigura-te ca branch-ul tau local "main" este la zi cu modificarile  din branch-ul "main" remote(de pe GitHub). Fiind pe branch-ul "main" local, faci un git pull de pe branch-ul "main" remote.
```
git pull origin main
```

<br/>

> 👉 Branch-ul tau local "main" fiind la zi, poti sa faci un alt branch "feature/task-2" care porneste din branch-ul "main".
```
git checkout -b feature/task-2
```

<br/>

> 👉 Noi in task-ul anterior nu am facut commit si push la toate fisierele. Momentan mai avem doua fisiere care sunt untracked de git(au culoarea rosie).
```
git status
```

<br/>

> 👉 Adauga ambele fisiere in git-ul tau local. De data asta in loc sa adaugam fiecare fisier in parte o sa adauga toate modificarile modificate.
```
git add .
```

<br/>

> 👉 Asigura-te ca fisierele tale sunt cu verde, adica adaugate in staged area.
```
git status
```

<br/>

> 👉 Adauga un commit
```
git commit -m "TASK 2 | Gata si task-ul 2" -m "Am mai invatat niste chestii noi."
```

<br/>

> 👉 Fa push pe remote(pe git-ul integrat/instalat in GitHub)
```
git push origin feature/task-2
```

<br/>

## Task 2 updates

<br/>

> Fiind un task mai complicat o sa lucreze doi developeri la el.
> Rezultatul final al taskului 2 este sa avem in fisierele "pretty-1.md" si "pretty-2.md" urmatorul text.

<br/>

```
I feel handsome
Oh so charming
It's alarming how charming I feel
And so cool
That I hardly can believe I'm real
```

## TASK 2.1

<br/>

> Pasi pentru developer 1

<br/>

> 👉 Fa un branch "feature/task-2.1" din branch-ul "feature/task-2"

<br/>

> 👉 Confirma ca esti pe branch-ul "feature/task-2"
```
git branch
```

<br/>

> 👉 Fa branch-ul "feature/task-2.1"
```
git checkout -b feature/task-2.1
```

<br/>

> 👉 Fa branch-ul "feature/task-2.1"

<br/>

> 👉 In fisierul "pretty-1.md" si "pretty-2.md" 
> Acceptance Criteria 1: schimba cuvantul "charming" cu "handsome".
> Acceptance Criteria 1: Inlocuieste randul 4 cu "++++++"
> Pentru task-2.1 fisierele "pretty-1.md" si "pretty-2.md"  trebuie sa contina
```
I feel handsome
Oh so charming
It's alarming how charming I feel
++++++
That I hardly can believe I'm real
```

<br/>

> 👉 Pune modificarile pe un branch remote
```
git add .
git commit -m "TASK 2.1 | Modificare 2.1"
git push origin feature/task-2.1
```

<br/>

> 👉 Fa un pull request prin care vrei sa faci mergi din "feature/task-2.1" in "feature/task-2"

<br/>

> 👉IMPORTANT: Nu da merge la pull request

## TASK 2.2

<br/>

> Pasi pentru developer 2

<br/>

> 👉 Fa un branch "feature/task-2.2" din branch-ul "feature/task-2"

<br/>

> 👉 Mai intai schimba-te inapoi pe branch-ul "feature/task-2"

```
git checkout feature/task-2
```

<br/>

> 👉 Da-i si un "git branch" ca sa confirmi

```
git branch
```

<br/>

> 👉 Creeaza branch-ul "feature/task-2.2" din branch-ul "feature/task-2"

```
git checkout -b feature/task-2.2
```

<br/>

> 👉 In fisierul "pretty-1.md" si "pretty-2.md" 
> Acceptance Criteria 1: langa cuvantul charming adauga "and sexy"
> Acceptance Criteria 2: sterge randu "And so pretty"
> Pentru task-2.2 fisierele "pretty-1.md" si "pretty-2.md" trebuie sa contina
```
I feel charming
Oh so charming
It's alarming how charming I feel
And so cool
That I hardly can believe I'm real
```

<br/>

> 👉 Pune modificarile pe un branch remote
```
git add .
git commit -m "TASK 2.2 | Modificare 2.2"
git push origin feature/task-2.1
```

## Task 2 updates

> 👉 Fa merge la branch-ul "feature/task-2.1" in "feature/task-2"

<br/>

> 👉 Fa merge la branch-ul "feature/task-2.2" in "feature/task-2"

<br/>

> 👉 Rezolva conflictele.

> 👉 Fa merge la "feature/task-2" in "main"


## Task 3

> Caute in commit-urile vechi si fa o ajustare  

git log --all --grep='Task 2.2'