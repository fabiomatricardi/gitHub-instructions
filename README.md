# gitHub-instructions
guide for local repo alignment


### Install GitHub CLI
winget upgrade --id GitHub.cli

### Git basic commands
git --version
git config --global user.name "Fabio Matricardi"
git config --global user.email "fabio.matricardi@gmail.com"


## GITHUB CLI MANUAL
https://cli.github.com/manual/gh_auth_login


# Start interactive setup
gh auth login



## CREATE A GITIGNORE
https://stackoverflow.com/questions/27850222/what-is-gitignore

https://git-scm.com/docs/gitignore

1. Init a new repo
```
git init
```


2.Create a remote GitHub repo
```
gh repo create --source=. --public --description "test advanced RAG AI"
```

✓ Created repository fabiomatricardi/KSdocs on GitHub
  https://github.com/fabiomatricardi/KSdocs
✓ Added remote https://github.com/fabiomatricardi/KSdocs.git

```
git add .
git status
git commit -m "comment to commit"
git branch -M main
git push -u origin main
```

