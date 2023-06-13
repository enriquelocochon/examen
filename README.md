# examen
examen web



LAB10-PC26@LAB10-PC26 MINGW64 ~
$ cd ..

LAB10-PC26@LAB10-PC26 MINGW64 /c/Users
$ cd ..

LAB10-PC26@LAB10-PC26 MINGW64 /c
$ cd examenMARS

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS
$ git init examen
Initialized empty Git repository in C:/examenMARS/examen/.git/

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS
$ cd examen

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git branch produccion
fatal: not a valid object name: 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ cd ..

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS
$ git branch
fatal: not a git repository (or any of the parent directories): .git

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS
$ git branch produccion
fatal: not a git repository (or any of the parent directories): .git

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS
$ cd examen

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git init
Reinitialized existing Git repository in C:/examenMARS/examen/.git/

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git branch --show current
master

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git branch produccion
fatal: not a valid object name: 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git checkout main
error: pathspec 'main' did not match any file(s) known to git

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ cd examen
bash: cd: examen: No such file or directory

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ cd ..

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS
$ git branch --show current
fatal: not a git repository (or any of the parent directories): .git

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS
$ cd examen

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git add https://github.com/enriquelocochon/examen.git
fatal: pathspec 'https://github.com/enriquelocochon/examen.git' did not match any files

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git branch produccion
fatal: not a valid object name: 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git branch produccion
fatal: not a valid object name: 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git add .

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git commit -m "ya??"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB10-PC26@LAB10-PC26.(none)')

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git config --global user.email"tic-280050@utnay.edu.mx"

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git config --global user.name "enriquelocochon"

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git commit -m "ya??"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB10-PC26@LAB10-PC26.(none)')

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git config user.mail

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git config user.email

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git commit -m "ya??"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB10-PC26@LAB10-PC26.(none)')

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git config --global user.name "enriquelocochon"

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git config --global user.email "tic-280050@utnay.edu.mx"

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git config user.name
enriquelocochon

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git commit -m "ya??"
[master (root-commit) 36c668b] ya??
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 e.txt

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git branch produccion

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git branch ventas

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git branch recursos_humanos

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git checkout produccion
Switched to branch 'produccion'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ cd Produccion
bash: cd: Produccion: No such file or directory

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git add materia-prima.txt
fatal: pathspec 'materia-prima.txt' did not match any files

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git status
On branch produccion
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git add .

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git commit -m "archivos produccion"
On branch produccion
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git status
On branch produccion
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git checkout ventas
Switched to branch 'ventas'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git add ventas.txt
fatal: pathspec 'ventas.txt' did not match any files

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git add ventas
fatal: pathspec 'ventas' did not match any files

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git status
On branch ventas
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git checkout recursos_humanos
Switched to branch 'recursos_humanos'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git status
On branch recursos_humanos
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git checkout master
Switched to branch 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git status
On branch master
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge origin main
merge: origin - not something we can merge

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge produccion
Already up to date.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge ventas
Already up to date.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge recursos_humanos
Already up to date.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git commit -m "hice merge"
On branch master
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git checkout produccion
Switched to branch 'produccion'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git status
On branch produccion
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git log
commit 36c668bbfc67785ee168407c9271eeb2ce20238c (HEAD -> produccion, ventas, recursos_humanos, master)
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 16:50:37 2023 -0700

    ya??

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git push origin produccion
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git checkout ventas
Switched to branch 'ventas'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git log
commit 36c668bbfc67785ee168407c9271eeb2ce20238c (HEAD -> ventas, recursos_humanos, produccion, master)
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 16:50:37 2023 -0700

    ya??

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git status
On branch ventas
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        empleados.txt
        imagenproducto.png
        materia-prima.txt
        productofinal.txt
        tiendas.txt.txt

nothing added to commit but untracked files present (use "git add" to track)

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git checkout produccion
Switched to branch 'produccion'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git add .

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git status
On branch produccion
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   empleados.txt
        new file:   imagenproducto.png
        new file:   materia-prima.txt
        new file:   productofinal.txt
        new file:   tiendas.txt.txt


LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git commit -m "meti todo"
[produccion a1f2e1c] meti todo
 5 files changed, 8 insertions(+)
 create mode 100644 empleados.txt
 create mode 100644 imagenproducto.png
 create mode 100644 materia-prima.txt
 create mode 100644 productofinal.txt
 create mode 100644 tiendas.txt.txt

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git checkout master
Switched to branch 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git status
On branch master
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge produccion
Updating 36c668b..a1f2e1c
Fast-forward
 empleados.txt      |   5 +++++
 imagenproducto.png | Bin 0 -> 519963 bytes
 materia-prima.txt  |   0
 productofinal.txt  |   0
 tiendas.txt.txt    |   3 +++
 5 files changed, 8 insertions(+)
 create mode 100644 empleados.txt
 create mode 100644 imagenproducto.png
 create mode 100644 materia-prima.txt
 create mode 100644 productofinal.txt
 create mode 100644 tiendas.txt.txt

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge ventas
Already up to date.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge recursos_humanos
Already up to date.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'origin'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git remote show origin
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git remote -v

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git remote add origin https://github.com/enriquelocochon/examen.git

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git remote -v
origin  https://github.com/enriquelocochon/examen.git (fetch)
origin  https://github.com/enriquelocochon/examen.git (push)

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin master
info: please complete authentication in your browser...
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (8/8), 504.80 KiB | 25.24 MiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/enriquelocochon/examen/pull/new/master
remote:
To https://github.com/enriquelocochon/examen.git
 * [new branch]      master -> master

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git pull origin main
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 602 bytes | 75.00 KiB/s, done.
From https://github.com/enriquelocochon/examen
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
fatal: refusing to merge unrelated histories

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git status
On branch master
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/enriquelocochon/examen.git'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git pull origin main
From https://github.com/enriquelocochon/examen
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge ventas
Already up to date.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge recursos_humanos
Already up to date.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git  log
commit a1f2e1cb38653e16c35ed2220608e91ba30c387d (HEAD -> master, origin/master, produccion)
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 17:09:49 2023 -0700

    meti todo

commit 36c668bbfc67785ee168407c9271eeb2ce20238c (ventas, recursos_humanos)
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 16:50:37 2023 -0700

    ya??

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git commit -m "primer version"
On branch master
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git log
commit a1f2e1cb38653e16c35ed2220608e91ba30c387d (HEAD -> master, origin/master, produccion)
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 17:09:49 2023 -0700

    meti todo

commit 36c668bbfc67785ee168407c9271eeb2ce20238c (ventas, recursos_humanos)
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 16:50:37 2023 -0700

    ya??

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git tag v.1

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin v.1
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/enriquelocochon/examen.git
 * [new tag]         v.1 -> v.1

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git checkout recursos_humanos
Switched to branch 'recursos_humanos'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git pull origin main
From https://github.com/enriquelocochon/examen
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git checkout master
Switched to branch 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git checkout recursos_humanos
Switched to branch 'recursos_humanos'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git checkout produccion
Switched to branch 'produccion'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (produccion)
$ git checkout ventas
Switched to branch 'ventas'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git checkout recursos_humanos
Switched to branch 'recursos_humanos'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git diff

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git add .

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git commit -m "mas empleadoos"
[recursos_humanos f50d67d] mas empleadoos
 1 file changed, 5 insertions(+)
 create mode 100644 empleados.txt.txt

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git diff

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git add .

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git status
On branch recursos_humanos
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   empleados.txt.txt


LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git commit -m "sexto nombre"
[recursos_humanos cd93b6a] sexto nombre
 1 file changed, 3 insertions(+)

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git diff

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git checkout master
Switched to branch 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git diff

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git status
On branch master
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge
fatal: No remote for the current branch.

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git diff

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git checkout recursos_humanos
Switched to branch 'recursos_humanos'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git status
On branch recursos_humanos
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git log
commit cd93b6ac8984659fb688b9cfb82bef03ed688931 (HEAD -> recursos_humanos)
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 17:29:22 2023 -0700

    sexto nombre

commit f50d67d1fcd7f45fbbfb366b8829652989957319
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 17:28:31 2023 -0700

    mas empleadoos

commit 36c668bbfc67785ee168407c9271eeb2ce20238c (ventas)
Author: enriquelocochon <tic-280050@utnay.edu.mx>
Date:   Mon Jun 12 16:50:37 2023 -0700

    ya??

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git diff

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (recursos_humanos)
$ git checkout ventas
Switched to branch 'ventas'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git diff

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (ventas)
$ git checkout master
Switched to branch 'master'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git merge recursos_humanos
Merge made by the 'ort' strategy.
 empleados.txt.txt | 8 ++++++++
 1 file changed, 8 insertions(+)
 create mode 100644 empleados.txt.txt

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git diff

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/enriquelocochon/examen.git'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin master
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (8/8), 839 bytes | 839.00 KiB/s, done.
Total 8 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/enriquelocochon/examen.git
   a1f2e1c..363bf40  master -> master

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git commit -m "merge del punto 8"
On branch master
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git status
On branch master
nothing to commit, working tree clean

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git tag v.1.1

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin tag v1.1
error: src refspec refs/tags/v1.1 does not match any
error: failed to push some refs to 'https://github.com/enriquelocochon/examen.git'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin --tag
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/enriquelocochon/examen.git
 * [new tag]         v.1.1 -> v.1.1

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/enriquelocochon/examen.git'

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ git push origin master
Everything up-to-date

LAB10-PC26@LAB10-PC26 MINGW64 /c/examenMARS/examen (master)
$ ^C
