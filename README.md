
# Git exercise review, is all about:

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
