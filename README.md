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
| git init                                 | Initialises current local directory as git repository folder                         |
| git config --list                        | List current configuration. TO EXIT LIST interface, type in :wq. Pressing ctrl+c does not work here.                    |
| git config --global user.name 'user'     | Attaches user details after initialisation                                     |
| git config --global user.email 'a@l.com' | Attaches user details after initialisation                                     |
| git clone                                | To copy from remote to offline                                                 |
| git status                               | Checks files + track directory changes. Have to be in repo file to execute     |
| git branch -u remote/branch              | Switches current tracked remote branch being compared to in git status command to 'remote/branch'. Also sets where the default branch being pulled from/pushed to is from the current branch.  |
| git branch -avv                          | Lists all local and remote branches in a -vv verbose manner             |
| git branch branch2                       | Add 'branch2' to repo timeline                                                 |
| git branch -D branchname                 | Deletes local branch 'branchname'. SHOULD be used IN CONJUNCTION with remote branch deletion command below for consistency.                                                 |
| git checkout branch1                     | Switch to branch 'branch1'                                                     |
| git checkout -b branch3                  | Create and switch to branch 'branch3'                                          |
| git add .                                | Put in staging area, . is to add all.                                          |
| git add *.html                           | Put in staging area, *.html adds all files ending in .html.                    |
| git rm --cached index.html               | Removes file from staging area.                                                |
| git rm -rf .git                          | Deletes .git folder. R means folder internals deleted, F means forced.  |
| git reset .                              | Unstages all files                                                             |
| git restore --staged .                             | PREFERRED. Unstages all files.                                                             |
| git commit -a -m 'Commit message'        | Commits all files with message to branch.                                      |
| git stash -u                             | Stashes saved changes so that files revert to before last commit.              |
| git stash pop                            | Pops changes to the current directory                                          |
| git merge branch2 --squash               | Branch2's small commits will register as 1 large commit in master history. BUT won't change head commit, need to add new commit on master  |
| git log                                  | Show commit history                                                            |
| git remote -v                            | List added remote directories. -v is verbose.                                  |
| git remote rename origin newname         | Rename remote 'origin' to 'newname'.                                           |
| git remote add origin http://...git      | Adds remote directory titled 'origin'                                          |
| git pull                                 | Pulls changes (fetch+merge) from ALL remote branches to ALL local branches     |
| git push origin branch2                  | Pushes changes from CURRENT checkedout branch to 'branch2' of remote 'origin'                             |
| git push origin :                        | Pushes changes from matching branches to 'origin'. If : is OMITTED, the command will push CURRENT branch to the tracked/configured branch from the branch -u command (I think)  |
| git push origin --all                    | Pushes changes from all branches locally to 'origin'                                   |
| git push origin :branchname              | DELETES the remote branch 'branchname' with the colon prefixed. SHOULD be used IN CONJUNCTION with branch -D command to delete the matching local branch as well.                      |
| touch readme.md                          | Creates a file                                                                 |
  

Summary of lessons learned:
  - **Git vs Hub**: Git is the actual version control software (VCS). Github is the web service using Git hosted on servers. People can use github/git only without interchanging.
  - **Push vs pull**: In git, pushing is to put updates onto the 'remote' github, pulling is to get updates from the remote. In Github, there are only pull requests, refering to merging changes of 2 branches.
  - **Purpose of Git**: Version control + collaboration for docs.
  - **Visualise timeline**: Graphs tab -> Network. Visualises branches.
  - **Contribute to projects**: Fork from open source project -> Clone -> Commit -> Git Push -> on GH can make pull request to original project page.
  - **Merging**: Pull-request is the request to change, merge is the actual action
  - **Pull-request page**: Can see commits, changes & conversatdion
  - **Issues page**: Use the issues tab to list comments on issues. Specific commits can be referenced by PASTING commit hash identifier into the comments and it will automatically be attached to the issue.
  - **Issue/Commit Titles**: If in the title of the commit, a specific issue number (i.e. 'blabla #10') is referenced, the issue will be attached to the commit as being addressed. The keyword 'fix' or 'fixed' can be added to title as well with number to automatically close issue.
  - **Local Repo Creation**: Use 'git init' in selected work folder to set as repo.
  - **Local to GitHub migration**: To push changes from an offline created repo, first create the repo on github w/o readme, then add remote, and push changes.
  - **Existing to New GitHub remote upload**: To upload to a new Github repo from an existing local project (i.e. cloned from another repo):
    1. Rename original remote from source:
       - *git remote rename origin upstream*
    2. Add in new destination remote:
       - *git remote add origin NEW_GH_URL*
    3. Push as usual:
       - *git push origin master*
    4. Pull in patches from upstream:
       - *git pull upstream master && git push origin master*
  - **GitHub pages**: change master into "gh-pages" and set as default under settings. Can be accesed via the link listed on the guthub pages section in settings. Create an index.html file as the default page accessed in the website.
  - **Git remote**: pull changes to branch, commit changes, checkout to master and merge branch, push changes to remote
  - **.gitignore**: List files/folders for git not to track (Separated by line - e.g. log.txt, /dir2). Usually applies to node modules and log files. Can use **vs code plugin** to generate defaults for environment quickly.
  - **Branch switching**: Every time switch branch, the current directory will reflect files of branch.
  - **Commit messages**: Use emojis in titles to get GH stars. Can be multi-line in terminal such that the preceding lines is the comment and 1st line is the title.
