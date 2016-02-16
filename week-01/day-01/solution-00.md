+ I encountered a problem with commiting the README.md file after someone else from the group updated it.

+ To solve this problem i:

+ removed the current directory from my local
+ cloned the repository again
+ pulled the updated files to my local
+ created my own markdown file with the required info
+ commited and merged it with the master in the 

To https://github.com/IronCoder1/front-end-course-students.git
   049d377..8cbe2ee  master -> master
MBP:front-end-course-students sos999now$ git pull https://github.com/fedosejev/front-end-course-students.git
remote: Counting objects: 36, done.
remote: Compressing objects: 100% (29/29), done.
remote: Total 36 (delta 1), reused 36 (delta 1), pack-reused 0
Unpacking objects: 100% (36/36), done.
From https://github.com/fedosejev/front-end-course-students
 * branch            HEAD       -> FETCH_HEAD
CONFLICT (modify/delete): README.md deleted in HEAD and modified in 8444bb2f36badd817c7ab5668b728e03fe850b76. Version 8444bb2f36badd817c7ab5668b728e03fe850b76 of README.md left in tree.
Automatic merge failed; fix conflicts and then commit the result.
MBP:front-end-course-students sos999now$ git log
commit 8cbe2ee326820d071b76a07a702b0db03b05e4d5

Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   ANTHONY.MD

MBP:front-end-course-students sos999now$ git commit -a -m "anthony contacts"clear
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean