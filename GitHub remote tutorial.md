# **Testing the git remote tools**

**Clone**

`git clone url`

**Change to the repository directory**

`cd \path\to\repository\directory`

**Minimal Configuration**

`git config --global user.name your_git_user_name`

`git config --global user.email your@user_email`

`--global` flag sets configuration options at a global level, if instead you want to set it at a project level use `--local`, instead.

**Commit**

`git commit -a -m "commit message"`

or

`git commit "file_to_commit" -m "commit message"`

`-a` tell the command to automatically stage files that have been modified and deleted, but new files you have not told Git about are not affected.

**Push**

`git push [remote-name] [branch-name]`

If you want to push your master branch to your `origin` server, then you can run to push any commits you've done

**Pull**

`git pull`

Automatically fetch and then merge that remote branch into your current branch. The `git clone` command automatically sets up your local master branch to track the remote master branch on the server you cloned from. Running `git pull` generally fetches data from the server you originally cloned from and automatically tries to merge it into the code you're currently working on.
 
**Add**

If you create a new file into your local repository and want to add it in to the remote repositoty.

`git add "file_name"`






