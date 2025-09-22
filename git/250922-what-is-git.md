# TODO

## 오늘 배운 것

- shell, vim command
- git
- git branch

## 내일 배울 것

- git branch(2)
- collaboration


# What is git?

git은 분산형 버전관리 시스템

## How to use git?

### 구조

Working directory - Stage - Local repo - Remote repo

### 명령어

```shell
$ git add main.py
$ git commit
$ git push origin main
```

# Branch

## 메모

- git add . git commit -m 습관화 하지 말자.

# What is branch?

코드가 독립적으로 변경될 수 있도록 하는 시스템

## How to use Branch?

```shell
$ git branch : branch 리스트 확인(로컬)

$ touch fizz.py

$ git branch fizz

$ git switch fizz: fizz 브랜치로 이동

$ git branch

$ vi fizz.py

$ cat fizz.py

$ python3 fizz.py

$ git status

$ git add fizz.py

$ git commit

$ git switch main

$ git diff main fizz

$ git merge fizz

$ cat fizz.py

$ git branch -D fizz

$ git branch

$ git push origin main
```
