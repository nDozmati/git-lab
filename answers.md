Answer 1:
git version 2.31.1.windows.1


Answer 2:
git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Nicolas Dozmati
user.email=nd371518@ohio.edu


Answer 3:
for "git add --help":
file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-add.html
for "git --help"
It supplies a list of common Git commands


Answer 4:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)


Answer 5:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md


Answer 6:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md


Answer 7:
On branch master
nothing to commit, working tree clean


Answer 8:
commit 2943f9ca8c0ab78d86b7a1de93d145660eadb0d8 (HEAD -> master)
Author: Nicolas Dozmati <nd371518@ohio.edu>
Date:   Thu May 13 14:12:25 2021 -0400

    Initial commit


Answer 9:
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean


Answer 10:
Changes did not update yet.


Answer 11:
Recommends that I "git pull ..."


Answer 12:
Changes made were updated locally.

remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 721 bytes | 103.00 KiB/s, done.
From https://github.com/nDozmati/git-lab
   f5402db..b93ac4a  main       -> origin/main
Updating f5402db..b93ac4a
Fast-forward
 README.md | Bin 90 -> 71 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)