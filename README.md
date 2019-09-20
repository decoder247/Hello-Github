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
* [SETTING UP GIT](https://help.github.com/en/articles/set-up-git#setting-up-git)

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


|                 Git Command              |                                        Details                                 |
|------------------------------------------|--------------------------------------------------------------------------------|
| git init                                 | Initialises current directory as git repository folder                         |
| git config --list                        | List current configuration.                                                    |
| git config --global user.name 'user'     | Attaches user details after initialisation                                     |
| git config --global user.email 'a@l.com' | Attaches user details after initialisation                                     |
| git clone                                | To copy from remote to offline                                                 |
| git status                               | Checks files + track directory changes. Have to be in repo file to execute     |
| git branch branch2                       | Add 'branch2' to repo timeline                                                 |
| git checkout branch1                     | Switch to branch 'branch1'                                                     |
| git add .                                | Put in staging area, . is to add all.                                          |
| git add *.html                           | Put in staging area, *.html adds all files ending in .html.                    |
| git rm --cached index.html               | Removes file from staging area.                                                |
| git commit -a -m 'Commit message'        | Commits all files with message to branch.                                      |
| git log                                  | Show commit history                                                            |
| git remote -v                            | List added remote directories. -v is verbose.                                  |
| git remote add origin http://...git      | Adds remote directory titled 'origin'                                          |
| git pull                                 | Pulls changes (fetch+merge) from ALL remote branches to ALL local branches     |
| git push origin branch2                  | Pushes changes branch 'branch2' of remote 'origin'                             |
| touch readme.md                          | Creates a file                                                                 |
  

Summary of lessons learned:
  - **Pull Request**: A request to merge changes from one branch to another branch. In GitHub only pull requests.
  - **Git vs Hub**: Git is the actual version control software (VCS). Github is the web service using Git hosted on servers. People can use github/git only without interchanging.
  - **Push vs pull**: In git, pushing is to put updates onto the 'remote' github, pulling is to get updates from the remote.
  - **Purpose of Git**: Version control and collaboration for docs.
  - **Visualise timeline**: Graphs tab -> Network. Visualises branches.
  - Post-forking, can make pull request to original project page
  - Pull-request is the request to change, merge is the actual action
  - Pull-request page can see commits, changes & conversation
  - Use the issues tab to list comments on issues. Specific commits can be referenced by PASTING commit hash identifier into the comments and it will automatically be attached to the issue.
  - If in the title of the commit, a specific issue number (i.e. 'blabla #10') is referenced, the issue will be attached to the commit as being addressed. The keyword 'fix' or 'fixed' can be added to title as well with number to automatically close issue.
  - When creating offline, first convert current working directory to git repo by using git init.
  - To push changes from an offline created repo, first create the repo on github w/o readme, then add remote, and push changes.
  - GitHub pages: change master into "gh-pages" and set as default under settings. Can be accesed via the link listed on the guthub pages section in settings. Create an index.html file as the default page accessed in the website.
  - Git remote: pull changes to branch, commit changes, checkout to master and merge branch, push changes to remote
