# Hello-Github
Understanding github by way of examples

---
## ▶ Next: Watch and note down git crash course video points, then vs code and begin C++ project.

---
### 💯 Progress:
##### Finished Coding Train Series + Crash Course
##### Understand most basic commands and git + github interactions

---
Good Resources:
* [Learning Lab](https://lab.github.com/)
* [try.github.io - Note cheat sheet!](https://try.github.io/)
* [github vs git](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)

Youtube tutorials:
1. [Git side-by-side (@6min)](https://www.youtube.com/watch?v=0fKg7e37bQE)
2. [Using VS Code (@1.5min)](https://www.youtube.com/watch?v=HkdAHXoRtos)
3. [Coding Train Series (@#9.13)](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
4. [Git/Hub crash course (@10min)](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

----------
* [Git in under 20 min (@3min)](https://www.youtube.com/watch?v=Y9XZQO1n_7c)
* [Git seminar explainer (@22min)](https://www.youtube.com/watch?v=1ffBJ4sVUb4&t=1320s)
* [Official, Github (@#2,5min)](https://www.youtube.com/watch?v=SCZF6I-Rc4I&list=PLg7s6cbtAD15Das5LK9mXt_g59DLWxKUe)
* [Official, Git (@6min)](https://www.youtube.com/watch?v=8oRjP8yj2Wo&list=PLg7s6cbtAD165JTRsXh8ofwRw0PqUnkVH&t=360s)


Useful git commands:
  - git clone https://.....git : To copy offline
  - git status (has to be in the file): To check files & track directory change
  - git branch tree: Adds 'tree' branch to repo timeline
  - git checkout master: Switch to master branch
  - git add . (. is to add all): To put into staging area
  - git commit -a -m "asdasdads" : To commit onto remote repo
    - if error follow msg to attach ur username + e-mail as author
  - git config --list
  - git log: shows commit history
  - IN git, pushing is to put updates onto the 'remote' or cloud github, pulling is to get updates from the remote
  - git remote -v: v stands for verbose. Command is used to know what name of remote to push to.
  - git remote add origin http//.. : To add remote when creating repo from offline
  - git push origin master: this pushes it to remote 'origin' and branch 'master'
  - touch readme.md: Creates a file called 'readme.md'
  

Summary of lessons learned:
  - A pull request is a request to potentially merge made changes from another branch to (commonly) the master
  - Git is the actual version control software (VCS). Github is the web service using Git hosted on servers.
  - People can use github only and git only without interchanging.
  - Git -> Version control and collaboration for documents/code.
  - Visualise branches under graphs tab -> network
  - Post-forking, can make pull request to original project page
  - Pull-request is the request to change, merge is the actual action
  - Pull-request page can see commits, changes & conversation
  - Use the issues tab to list comments on issues. Specific commits can be referenced by PASTING commit hash identifier into the comments and it will automatically be attached to the issue.
  - If in the title of the commit, a specific issue number (i.e. 'blabla #10') is referenced, the issue will be attached to the commit as being addressed. The keyword 'fix' or 'fixed' can be added to title as well with number to automatically close issue.
  - When creating offline, first convert current working directory to git repo by using git init.
  - To push changes from an offline created repo, first create the repo on github w/o readme, then add remote, and push changes.
  - GitHub pages: change master into "gh-pages" and set as default under settings. Can be accesed via the link listed on the guthub pages section in settings. Create an index.html file as the default page accessed in the website.
  - Git remote: pull changes to branch, commit changes, checkout to master and merge branch, push changes to remote
