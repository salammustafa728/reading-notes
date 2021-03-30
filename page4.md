[Home](README.md)

About Git:
Github is collaborative system we can share our work inro it.
we need to create a repository then you clone it to make changes offline then you can push it agian to the github 
the artical explain how to started with github and make an account then how to install it on our device step by step this the link for install it for windows: You can download Git by visiting this link and following the posted directions:
http://git-scm.com/download/win
after that we should learn how to sit up a git repository then you need to push your work on the github using git by A-C-P (Add,Commit,Push)
$ git add .
$ git commit -m “any message here”
$ git push origin main
Cloning
You can also create a copy of an existing Git repository
$ git clone https://github.com/test mydirectory
 The Life Cycle of File Status
After you edit a file, Git flags it as modified because of changes made after the previous commit.
You stage the modified file.
Then, you commit staged changes.
Remote Repositories
 Teams can use remote repositories to push information to and pull data from
Seeing Your Remotes
$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)
Adding Remotes
git remote add shortname url