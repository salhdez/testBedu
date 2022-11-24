# Git session 1
```
echo "# testBedu">>README.md
```
```
git init
Initialized empty Git repository in C:/Users/sesparza/Documents/DevLab/bedu/testBedu/.git/
```
```
git add .
```
```
git commit -m "First commit"
[master (root-commit) 6f7d260] First commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
```
```
git branch -M main
```
```
git remote add origin https://github.com/salhdez/testBedu.git
```
```
git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 234 bytes | 117.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/salhdez/testBedu.git
 * [new branch]      main -main
Branch 'main' set up to track remote branch 'main' from 'origin'.
```
Comando específico para PowerShell:
```
$PSDefaultParameterValues['*:Encoding'] = 'utf8'
```
```
git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
```
```
code .
```
```
git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)
```
```
git add .
```
```
git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html
```
```
git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 619 bytes | 22.00 KiB/s, done.
From https://github.com/salhdez/testBedu
   6f7d260..d7eb37a  main       -origin/main
Updating 6f7d260..d7eb37a
Fast-forward
 README.md | Bin 26 -11 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)
```
```
git commit -m "Añadiendo index.html"
[main 7f32675] Añadiendo index.html
 1 file changed, 12 insertions(+)
 create mode 100644 index.html
```
```
git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 481 bytes | 160.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/salhdez/testBedu.git
   d7eb37a..7f32675  main -main
Branch 'main' set up to track remote branch 'main' from 'origin'.
```
```
git add .gitignore
```
