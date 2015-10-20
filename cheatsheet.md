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
