# FE--Tryouts
HTML &amp; CSS Tryouts
author: MN
we can edit this draft any time.

# INITIALISING GIT REPOS FROM LOCAL TO REMOTE REPOS.
cd_folder-name       to go into disired folder.
cd ..                to exit from a specific folder.
clear                to clear terminal.
git clone "#link"    to clone desired github repo into local machine.
ls                   to show all the available file and local github repos.
                     whenever folders are made in system, two types of files are created...:_    1. shown   and  2. hidden  -these can be accessed by terminal only.
ls -a                to access these hidden files.

till now only clone is made.
...........................................................| 
"STATUS" - shows the status of our code.
:
UNTRACKE-  New files that git does'nt yet track.
MODIFIEd-  changed files or modified files w/o commit.
STAGED-    file is ready to be commited (afted ADD).
UNMODIFIED- unchanged.
...........................................................|

git status                          for status(on branch main).
                                    (changes not staged for commit) when a file is modified locally.
                                    after modyfing any file there is a two-step process to commit our changes : 1.ADD  2.COMMIT.

git add "#link"                     to add a modified file before commit (can be verified on status).
                                    also, if too many files are to be added together then we can just type "git add ." (dot) and all files will get added together automtaically.

git commit -m "meaningfull msg"     RECORD  of changes:
                                    to commit an added file.(can be varified on status).

git push origin main                to finally upload local repo content from local repo (machine) to remote repo file(git).

git status...git ls...git add...