# this is my cheatsheet for github.com

### start new project

```shell
$ mkdir project name
$ git init
$ git touch readme.md
$ git add readme.md
$ git commit -m "Innitial commit"
```
### Do some work then save it

```shell
$ git status
$ git add <whatever file>
$ git status
$ git commit -m "This is the message"
```
### sharework with the world!!!

```shell
$ git remote add origin <the destination http/ssh key>
$ git push -u origin master
```
### forking
__Find code.. fork code.. clone code to separate repo__

```shell
$ git clone <Cloning destination>
```

then make some changes you think are worth changing

```shell
$ git add <your file>
$ git commit -m "explanation"
$ git push origin master
```

file a pull request*** IMPORTANT DO NOT FORGET THAT THIS IS SIMPLE>>> NOT MAGIC

sss

To create a branch of a file use git branch <name of the branch you want>
use git checkout to switch in between them

```shell
$ git branch <branch name here>
$ git checkout <branch to switch to>
$ git checkout master
$ git merge <branch name>
```



### Typical colaboration patterns

A typical flo is fork then branch off master. Do work on branch. add and commit info to branch. checkout branch to master then merge branches.
push info to github and submit pull request.



### adding aliases

Git doesn’t automatically infer your command if you type it in partially. If you don’t want to type the entire text of each make these changes:

```shell
$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
```

