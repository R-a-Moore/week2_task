# Explaining Github

![github / localhost, diagram]()

Github is like a constant communication relay, which is occuring between your local host (your personal machine that you're working on), and your online repository (which is stored on the cloud).

## Navigating in Commandline

- `cd ` navigates to base directory

- `cd ..` navigates back to previously visited directory

- `cd "file path"` navigates to specific directory

- `rm -rf "file name"` deletes file

- `ls` lists files present in current directory

- `ls -a` lists all (hidden) files in current directory

- `cat "file name"` exposes/presents content of specific file

- `pwd` presents current directory's filepath

## Creating a new Repo
Follow these steps if you wish to initialize and commit, push work to your repository. You would have needed to already create repository in your github online:

1. `git init` initializes a local git repository in the current directory. You should do this in a local directory which is named the same as your online repository so as not to confuse your later self or colleagues.

2. `git add .` adds all file contents to the index that will be committed `git add "file name"` adds a specific file content to the index.

3. `git commit -m "commit message"` records the changes applied in the add to the local repository.

4. `git branch -M "desired branch"` makes git work on the desired branch of the repository, as there may be several working branches. Note; can be done either before or after the `git add` command.

5. `git add remote origin "repo link"` links your local host repo to your online one so that it knows where to push/pull from.

6. `git push` updates the remote repo with new work and refs produced.

## Working on an existing repo
Note that you should only need to do one of each of these for their specific purpose: 

- `git clone` clones a respoitory into a new directory

- `git pull` fetches from your online repository and integrates to your local host branch.

- `git merge` joins two or more development histories together from your localhost and the online repository.
