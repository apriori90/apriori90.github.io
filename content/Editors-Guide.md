---
title: Editor's Guide
---

To edit anything on this website or add a meeting log, perform the following steps.

First, create account on GitHub and install/configure Git on your system such that it associate with your GitHub account. You need nodejs/npm too.

# Repository Cloning and Setup
```bash
git clone git@github.com:apriori90/apriori90.github.io.git

cd apriori90.github.io  # enter the directory

npm i  # install every required packages

```

# Adding new Entry/Edit/Log
```bash
git pull  # this step is not required if you just cloned it. but run this every time before you create a new branch from now on.

git branch 3rd-meeting-log  # create the working branch with the name you prefer.

git checkout 3rd-meeting-log  # activate the branch you just created in the current environment.

emacs ./content/meeting/20241223.md  # create/open the meeting log file (markdown) with the editor of your choice.
```

# Deploying Changes
You can do this part with [GitHub Desktop Application](https://github.com/apps/desktop) if you want.
```bash
git add --all  # add every changes you made
git commit -m "I just added today's meeting log"  # committing diff file with commit message
git push  # push every local changes to the GitHub server
```

# Creating a Pull Request (PR)
Our main branch is `v4` instead of `main`, following the Quartz configuration.
Henceforth, newly created branch (e.g. `3rd-meeting-log`) have to get merged with `v4`, and Pull Request is an application for that like its name suggests.

See this official [Pull Request Guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
