# testHW-1
test Link
Last login: Tue Jan 24 21:08:38 on ttys000
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ clear






















shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ clear























shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ cd cd ~/desktop/project
-bash: cd: cd: No such file or directory
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ /Users/shuoqiaoliu/Desktop/project 
-bash: /Users/shuoqiaoliu/Desktop/project: is a directory
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ git init
Initialized empty Git repository in /Users/shuoqiaoliu/.git/
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ ls -la
total 48
drwxr-xr-x+ 28 shuoqiaoliu  staff    952 Jan 24 22:06 .
drwxr-xr-x   6 root         admin    204 Jan 20 13:20 ..
-r--------   1 shuoqiaoliu  staff      7 Jan 20 13:55 .CFUserTextEncoding
-rw-r--r--@  1 shuoqiaoliu  staff  14340 Jan 22 13:11 .DS_Store
drwx------   4 shuoqiaoliu  staff    136 Jan 24 21:55 .Trash
-rw-------   1 shuoqiaoliu  staff   1853 Jan 24 21:08 .bash_history
drwx------  21 shuoqiaoliu  staff    714 Jan 24 21:12 .bash_sessions
drwxrwxrwx   4 shuoqiaoliu  staff    136 Jan 22 11:13 .config
drwx------   3 shuoqiaoliu  staff    102 Jan 20 22:25 .cups
drwx------   9 shuoqiaoliu  staff    306 Jan 22 10:16 .dropbox
drwxr-xr-x   9 shuoqiaoliu  staff    306 Jan 22 22:35 .eclipse
drwxr-xr-x  10 shuoqiaoliu  staff    340 Jan 24 22:06 .git
drwxr-xr-x   3 shuoqiaoliu  staff    102 Jan 20 17:10 .oracle_jre_usage
drwxr-xr-x   8 shuoqiaoliu  staff    272 Jan 23 23:56 .p2
drwxr-xr-x   3 shuoqiaoliu  staff    102 Jan 22 22:12 .tooling
drwx------@  3 shuoqiaoliu  staff    102 Jan 20 16:45 Applications
drwxr-x---   3 shuoqiaoliu  staff    102 Jan 22 09:10 Blizzard
drwx------+  5 shuoqiaoliu  staff    170 Jan 24 21:35 Desktop
drwx------+  4 shuoqiaoliu  staff    136 Jan 22 22:12 Documents
drwx------+ 10 shuoqiaoliu  staff    340 Jan 24 20:01 Downloads
drwx------@ 13 shuoqiaoliu  staff    442 Jan 24 20:52 Dropbox
drwx------@ 61 shuoqiaoliu  staff   2074 Jan 22 09:36 Library
drwx------+  3 shuoqiaoliu  staff    102 Jan 20 13:08 Movies
drwx------+  3 shuoqiaoliu  staff    102 Jan 20 13:08 Music
drwx------+  6 shuoqiaoliu  staff    204 Jan 22 12:57 Pictures
drwxr-xr-x+  5 shuoqiaoliu  staff    170 Jan 20 13:08 Public
drwxrwxrwx  16 shuoqiaoliu  staff    544 Jan 20 18:40 Qt
drwxr-xr-x   3 shuoqiaoliu  staff    102 Jan 20 17:10 eclipse
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ git add index.html
fatal: pathspec 'index.html' did not match any files
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.CFUserTextEncoding
	.Trash/
	.bash_history
	.bash_sessions/
	.config/
	.cups/
	.dropbox/
	.eclipse/
	.oracle_jre_usage/
	.p2/
	.tooling/
	Applications/
	Blizzard/
	Desktop/
	Documents/
	Downloads/
	Dropbox/
	Library/
	Movies/
	Music/
	Pictures/
	Public/
	Qt/
	eclipse/

nothing added to commit but untracked files present (use "git add" to track)
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ git add index.html
fatal: pathspec 'index.html' did not match any files
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ cd ~/Users/shuoqiaoliu/Desktop/project 
-bash: cd: /Users/shuoqiaoliu/Users/shuoqiaoliu/Desktop/project: No such file or directory
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ git init
Reinitialized existing Git repository in /Users/shuoqiaoliu/.git/
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ ls -la
total 48
drwxr-xr-x+ 28 shuoqiaoliu  staff    952 Jan 24 22:06 .
drwxr-xr-x   6 root         admin    204 Jan 20 13:20 ..
-r--------   1 shuoqiaoliu  staff      7 Jan 20 13:55 .CFUserTextEncoding
-rw-r--r--@  1 shuoqiaoliu  staff  14340 Jan 22 13:11 .DS_Store
drwx------   4 shuoqiaoliu  staff    136 Jan 24 21:55 .Trash
-rw-------   1 shuoqiaoliu  staff   1853 Jan 24 21:08 .bash_history
drwx------  21 shuoqiaoliu  staff    714 Jan 24 21:12 .bash_sessions
drwxrwxrwx   4 shuoqiaoliu  staff    136 Jan 22 11:13 .config
drwx------   3 shuoqiaoliu  staff    102 Jan 20 22:25 .cups
drwx------   9 shuoqiaoliu  staff    306 Jan 22 10:16 .dropbox
drwxr-xr-x   9 shuoqiaoliu  staff    306 Jan 22 22:35 .eclipse
drwxr-xr-x  10 shuoqiaoliu  staff    340 Jan 24 22:12 .git
drwxr-xr-x   3 shuoqiaoliu  staff    102 Jan 20 17:10 .oracle_jre_usage
drwxr-xr-x   8 shuoqiaoliu  staff    272 Jan 23 23:56 .p2
drwxr-xr-x   3 shuoqiaoliu  staff    102 Jan 22 22:12 .tooling
drwx------@  3 shuoqiaoliu  staff    102 Jan 20 16:45 Applications
drwxr-x---   3 shuoqiaoliu  staff    102 Jan 22 09:10 Blizzard
drwx------+  5 shuoqiaoliu  staff    170 Jan 24 21:35 Desktop
drwx------+  4 shuoqiaoliu  staff    136 Jan 22 22:12 Documents
drwx------+ 10 shuoqiaoliu  staff    340 Jan 24 20:01 Downloads
drwx------@ 13 shuoqiaoliu  staff    442 Jan 24 20:52 Dropbox
drwx------@ 61 shuoqiaoliu  staff   2074 Jan 22 09:36 Library
drwx------+  3 shuoqiaoliu  staff    102 Jan 20 13:08 Movies
drwx------+  3 shuoqiaoliu  staff    102 Jan 20 13:08 Music
drwx------+  6 shuoqiaoliu  staff    204 Jan 22 12:57 Pictures
drwxr-xr-x+  5 shuoqiaoliu  staff    170 Jan 20 13:08 Public
drwxrwxrwx  16 shuoqiaoliu  staff    544 Jan 20 18:40 Qt
drwxr-xr-x   3 shuoqiaoliu  staff    102 Jan 20 17:10 eclipse
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$ git add index.html
fatal: pathspec 'index.html' did not match any files
shuoqiaos-MacBook-Pro:~ shuoqiaoliu$   cd ~/Desktop/project
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git init
Initialized empty Git repository in /Users/shuoqiaoliu/Desktop/project/.git/
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ ls -la
total 16
drwxr-xr-x   5 shuoqiaoliu  staff  170 Jan 24 22:16 .
drwx------+  5 shuoqiaoliu  staff  170 Jan 24 21:35 ..
drwxr-xr-x  10 shuoqiaoliu  staff  340 Jan 24 22:16 .git
-rw-r--r--@  1 shuoqiaoliu  staff  185 Jan 24 22:04 about.html
-rw-r--r--@  1 shuoqiaoliu  staff  191 Jan 24 22:02 index.html
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ add index.html
-bash: add: command not found
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git add index.html
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	about.html

shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git add .
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   about.html
	new file:   index.html

shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git commit -m"revision one"
[master (root-commit) 3568d3e] revision one
 Committer: shuoqiao liu <shuoqiaoliu@shuoqiaos-MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 26 insertions(+)
 create mode 100644 about.html
 create mode 100644 index.html
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
nothing to commit, working tree clean
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git log
commit 3568d3ee1e5fba60fcf56d994399a8e5eac13b6d
Author: shuoqiao liu <shuoqiaoliu@shuoqiaos-MacBook-Pro.local>
Date:   Tue Jan 24 22:20:34 2017 -0800

    revision one
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git checkout index.html
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git add.
git: 'add.' is not a git command. See 'git --help'.

Did you mean this?
	add
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git add .
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   index.html

shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   index.html

shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git reset HEAD index.html
Unstaged changes after reset:
M	index.html
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
shuoqiaos-MacBook-Pro:project shuoqiaoliu$  git add . 
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   index.html

shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git commit -m "revision two"
[master 1dd2ec9] revision two
 Committer: shuoqiao liu <shuoqiaoliu@shuoqiaos-MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 3 insertions(+), 3 deletions(-)
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
nothing to commit, working tree clean
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git add index.html
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   index.html

shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git commit -m "revision three"
[master 409e6d3] revision three
 Committer: shuoqiao liu <shuoqiaoliu@shuoqiaos-MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 2 insertions(+), 2 deletions(-)
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git status
On branch master
nothing to commit, working tree clean
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git log
commit 409e6d303f03acab238647c95b335dc4b274b396
Author: shuoqiao liu <shuoqiaoliu@shuoqiaos-MacBook-Pro.local>
Date:   Tue Jan 24 22:40:00 2017 -0800

    revision three

commit 1dd2ec9cf330517f7f6b05c1776a8806ff900508
Author: shuoqiao liu <shuoqiaoliu@shuoqiaos-MacBook-Pro.local>
Date:   Tue Jan 24 22:36:42 2017 -0800

    revision two

commit 3568d3ee1e5fba60fcf56d994399a8e5eac13b6d
Author: shuoqiao liu <shuoqiaoliu@shuoqiaos-MacBook-Pro.local>
Date:   Tue Jan 24 22:20:34 2017 -0800

    revision one
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git remote add origin https://github.com/JoeLiuCS/testHW-1.git
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git push -u origin master
Username for 'https://github.com': JoeLiuCS
Password for 'https://JoeLiuCS@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/JoeLiuCS/testHW-1.git/'
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git remote add origin https://github.com/JoeLiuCS/testHW-1.git
fatal: remote origin already exists.
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git push -u origin master
Username for 'https://github.com': JoeLiuCS
Password for 'https://JoeLiuCS@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/JoeLiuCS/testHW-1.git/'
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git remote add origin https://github.com/JoeLiuCS/testHW-1.git
fatal: remote origin already exists.
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ git push -u origin master
Username for 'https://github.com': JoeLiuCS
Password for 'https://JoeLiuCS@github.com': 
Counting objects: 10, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (10/10), done.
Writing objects: 100% (10/10), 1.17 KiB | 0 bytes/s, done.
Total 10 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/JoeLiuCS/testHW-1.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
shuoqiaos-MacBook-Pro:project shuoqiaoliu$ 
