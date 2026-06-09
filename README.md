

# Git exercise review, is all about:

## Git exercise review, is all about:


1. Reviewing same learning (for who knew nothing about git).
2. Learning how to create a repository in github.
3. Learning how to create, switch and delete branches in terminal.
4. Learning how to push and pull to/from github.
5. And so many other basics


### It is recommended to everyone trying to be a software developer!!
## Enjoy the BASICS of git😊🥂.





# Git exercise solutions

## Bundle-1

### Exercise-1


```bash
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git init
Reinitialized existing Git repository in /home/gift-of-god/Desktop/Git exercises/.git/
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git branch -m master
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git add .
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git commit -m "inital commit"
[master (root-commit) d811c3e] inital commit
 1 file changed, 13 insertions(+)
 create mode 100644 index.html
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git remote add origin https://github.com/Gift-250/Git-exercises-review.git
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git branch -m main
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 377 bytes | 377.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Gift-250/Git-exercises-review.git
 * [new branch]      main -> main
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git checkout -b dev
Switched to a new branch 'dev'
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git checkout -b test
Switched to a new branch 'test'
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git switch dev
Switched to branch 'dev'
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git branch -d test
Deleted branch test (was d811c3e).

```

### Exercise-2


```bash

gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git stash
No local changes to save
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git stash -u
Saved working directory and index state WIP on main: a22d7d1 Resolve README conflict on main branch
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git stash -u
Saved working directory and index state WIP on main: a22d7d1 Resolve README conflict on main branch
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git stash -u
Saved working directory and index state WIP on main: a22d7d1 Resolve README conflict on main branch
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git stash list
stash@{0}: WIP on main: a22d7d1 Resolve README conflict on main branch
stash@{1}: WIP on main: a22d7d1 Resolve README conflict on main branch
stash@{2}: WIP on main: a22d7d1 Resolve README conflict on main branch
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git stash pop stash@{1}
Already up to date.
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped stash@{1} (d57362a4a33aba1dfe76bd2d15929c7edd529632)
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git stash pop stash@{1}
Already up to date.
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        home.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped stash@{1} (9565156ad4a3c3f3f272ade1579c2b0273a3ec67)
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git add .
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git commit -m "Bundle-1 exercise-2 first commit"
[main 17d17be] Bundle-1 exercise-2 first commit
 2 files changed, 26 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 572 bytes | 286.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Gift-250/Git-exercises-review.git
   a22d7d1..17d17be  main -> main
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git stash pop
Already up to date.
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped refs/stash@{0} (27e70126975999ac4ba63ca15a1708d76a66de03)
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ git reset --hard HEAD
HEAD is now at 17d17be Bundle-1 exercise-2 first commit
gift-of-god@gift-of-god-HP-EliteBook-830-G6:~/Desktop/Git exercises$ 

```


