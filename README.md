# expert-spoon

This repository is created during __Git__ & __Github__ teaching sessions in times of COVID-19 precautionary holidays. The session was delivered using ZOOM. The Repository name __expert-spoon__ was suggested by GitHub itself. 

__Below is the summary of what is discussed.__

### Session 1:
+ I started off with the below mentioned introductory question. 
  + What is git?
  + What is Github?
  + What are alternatives to Github?
  + Why Github?
+ Later On, We moved to the installation of git & Github account setup. 
+ Work began with creating a repository on Github and cloning to the local machine. 
  ```bash
  $ git clone git@github.com:merrcury/expert-spoon.git
  ```
+ Discussed use of `git status`. Performed `git status` after each command for better understanding. 
+ What is tracked & untracked changes? & What is the function of `git add` and some simpler ways to use it.
  ```bash
  $ git add <filename> # To track single file
  $ git add . # To track all change
  ```
  + Using __-a__ in `git commit`. Discussed after `git commit`. 
+ Commiting Changes is next in the list. 
  ```bash
  $ git commit -m"Your_Message" #Commiting tracked changes
  $ git commit -a -m"Your_Message" #Tracking untracked changes & commiting them. 
  $ git commit -am"Your_Message" #Same functionality as above
  ```
+ Pushing Changes to Remote Repository. 
  ```bash
  $ git push origin master # Taught what is Git & Github work with this command?
  $ git push #Taught What is difference does origin master make?
  ```
+ Next on the list was checking for changes in the remote repository. 
  ```bash
  $ git fetch
  ```
+ Pulling those changes comes after that. 
  ```bash 
  $ git pull
  ```
+ After all this, How one can look back at progress? Introduced log.
  ```bash
  $ git log
  ```
+ It's was time for thrilling part. Yes, I discussed Merge Conflicts. 
  + What is merge conflicts?
  + How they generally occur?
  + How to resolve them?
  + In Session, I taught How to solve them using interactive Text Editors and IDEs? Using `git mergetool` is scheduled for further sessions. 
  + Discussed When to accept _Current Changes_, _Incoming Changes_, _Both Changes_ & _No Change_. 
  + Played for a bit with Merge Conflicts. 
+ At last, Taught How to add existing git repo to a Remote. 
  ```bash 
  $ git remote add origin git@github.com:merrcury/expert-spoon.git
  $ git remote -v #Validating
  ```
+ Ended Session with QnA

## LICENSE
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">expert-spoon</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/merrcury/expert-spoon/" property="cc:attributionName" rel="cc:attributionURL">Himanshu Garg</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
