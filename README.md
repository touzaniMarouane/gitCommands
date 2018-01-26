# gitCommands
## Command line instructions

### Git global setup
```bash
git config --global user.name "user name"
git config --global user.email "your@email"
```

### Create a new repository
git clone https://github.com/user.name/repo-name.git
```bash
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```

### Existing folder
```bash
cd existing_folder
git init
git remote add origin https://github.com/user.name/repo-name.git
git add .
git commit -m "Initial commit"
git push -u origin master
```

### Existing Git repository
```bash
cd existing_repo
git remote rename origin old-origin
git remote add origin https://github.com/user.name/repo-name.git
git push -u origin --all
git push -u origin --tags
```
