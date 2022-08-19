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
