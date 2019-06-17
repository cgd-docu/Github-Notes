# Git Basic Workflow with GitHub

## Table of contents

- [Git Configuration](#user-content-git-configuration--user-and-email-)
- [Copy Repository to Local Computer](#user-content-copy-repository-to-local-computer)
- [Git Commit](#user-content-git-commit)
- [Git Push to Remote Repo](#user-content-git-push-to-remote-repo)

### Git Configuration ( User and Email )

```text
$ git config --global user.name "Christian D"
$ git config --global user.email "chrisgen@gmail.com"
```

to check the git config, use :

```text
$ git config --global --list
```

### Copy Repository to Local Computer

```text
$ git clone < git repo >
```

### Git Commit

```text
$ git add .
$ git add < name.txt >
$ git commit -m "< commit desc >"
$ git status
```

### Git Push to Remote Repo

```text
$ git push origin master
```
