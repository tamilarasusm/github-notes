# github-notes 

### Setting Up a Git Repository

- Initialize an empty Git repo in the current project in your local.
```
git init
```

- Clone the repository from remote origin.
```
git clone https://github.com/<USERNAME>/<REPO>.git
```

- Clone the repository from remote origin to the new folder name instead of remote folder name
```
git clone https://github.com/<USERNAME>/<REPO>.git <NEW_FOLDER_NAME>
```

- Point remote repository to the local
```
git remote add origin https://github.com/<USERNAME>/<REPO>.git
```

### Fetching Latest Changes From Git Repository

- Get the latest changes from the remote origin and merge them.
```
git pull
```

- Get the latest changes from the remote origin but not merge them.
```
git fetch
```

### Add Local Changes

- Add latest changes to staging without deletions on the current and subdirectories
```
git add .
```

- Add all changes to staging (With deletions, newly added files and modification files)
```
git add -A
```

- Add list of files changes to the staging
```
git add <filenames>
```

### Local changes file status

-Get the status of the staging with tracked and untracked file changes 
```
git status
```

-Shows unstaged changes in the index and the working directory.
```
git diff
```
