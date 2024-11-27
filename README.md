# Github-Commands
Every new laptop purchase?
<ol>
<li> Git software install https://git-scm.com/download/win</li>
<li> git config --global user.name "yourname"</li>
<li> git config --global user.email "youremail@gmail.com"</li>
</ol>

## Every new project?
<ol>
  <li> git init</li>
  <li> git remote add origin "remote url/path"</li>

</ol>

## Every new file added/change/delete?
<ol>
  <li> git add . </li>
  <li> git commit -m "initial commit"</li>
    <li> git branch -M main</li>
   <li> git remote add origin "remote url/path"</li>
  <li> git push origin main</li>
</ol>

<ol>
<h2>More commands</h2>
<li>status check        :-> git status</li>
<li>remote repo         :-> git remote -v</li>
<li>change name         :-> git branch -M main</li>
<li>new branch          :-> git branch name <main></li>
<li>current branch      :-> git branch</li>
<li>switch branch       :-> git checkout <name></li>
<li>switch & create branch:-> git checkout -b <name></li>
<li>delete branch       :-> git branch -d <name></li>
<li>git & github</li>
</ol>

# **Version Control with Git**

**Commands**

- git clone (create a local copy of the remote repo)
- git add
- git commit
- git log
- git push
- git pull
- git init
- git remote add origin <remote_repo>
- git push - -set-upstream origin master (create local git repo and connect to remote repo)
- git checkout
- git checkout -b (create a new branch locally)
- git branch
- git status
- git branch -d
- git rebase(avoid unnecessary merge commits in git history)
- git rm -r - -cached
- git rm - -cached (remove file from remote repo)
- git stash
- git stash pop(save unfinished changes)
- git reset - -hard HEAD~1(revert & discard changes to commit
- git reset HEAD~1(revert & keep changes)
- git commit - -amend(merge changes into last commit)
- git reset - -hard HEAD~1
- git push - -force
- git revert <commit_hash>(creates new commit to revert old commit changes)
- git merge

**Remove Git**

remove local .git file (contains config for git remotes etc) rm -fr .git

**best practices**

1 branch per feature dev branch: intermediary master branch pull/merge requests delete branch when merged add a .gitignore file
