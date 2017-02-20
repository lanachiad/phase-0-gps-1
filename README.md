# README for first GPS

gps (master #) :> git clone https://github.com/lanachiad/phase-0-gps-1.git

	Creates exact clone of the repo on a remote machine onto your local one.

phase-0-gps-1 (master) :> git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	awesome_page.md

nothing added to commit but untracked files present (use "git add" to track)

	Shows working status of files on active branch. 

phase-0-gps-1 (master) :> git add awesome_page.md

	Changes status of file from untracked to staged.

phase-0-gps-1 (master +) :> git commit -m "Added awesome_page.md"
[master f54f304] Added awesome_page.md
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 awesome_page.md

 	Changes status of file from staged to committed. 

phase-0-gps-1 (master) :> git push origin master
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 319 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/lanachiad/phase-0-gps-1.git
   7478c64..f54f304  master -> master

   Pushes changes made on the feature branch to the remote repo.

phase-0-gps-1 (master) :> git checkout -b add-command-log
Switched to a new branch 'add-command-log'

	Creates new feature branch from the current branch and switches to it.