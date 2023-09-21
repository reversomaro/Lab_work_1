pwd

/home/user

- mkdir projects

cd projects

~ pwd

/home/user/projects



- git clone https://github.com/user/Lab_work_1.git

 Cloning into 'Lab_work_1'...

 remote: Counting objects: 3, done

.

 remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 15 Unpacking objects: 100% (3/3), done.

 Checking connectivity... done.



18 ~ls

19 Lab_work_1

28

21 - cd Lab_work_1

22

23 ls

24 README.md


~ pwd
/home/user

~ mkdir projects

~ cd projects

~ pwd
/home/user/projects

~ git init
Initialized empty Git repository in https://github.com/user/Lab_work_1.git

~ touch README.md

~ git add README.md

~ git commit -m "Initial commit."
[master (root-commit) 3637301] Initial commit.
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

~ git remote add origin https://github.com/user/Lab_work_1.git

~ git push -u origin master
Username for 'https://github.com': user
Password for 'https://user@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 218 bytes | 218.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/user/Lab_work_1.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.


~ touch main.cpp
~ git status

On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        main.cpp

nothing added to commit but untracked files present (use "git add" to track)

~ git add main.cpp
~ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   main.cpp

        % git commit -m "Added project files."
[master 275127f] Added project files.
 3 files changed, 90 insertions(+)
 create mode 100644 main.cpp
 % git push

Username for 'https://github.com': user
Password for 'https://user@github.com': 
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 913 bytes | 0 bytes/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/user/Lab_work_1.git
   fef3301..275127f  master -> master


