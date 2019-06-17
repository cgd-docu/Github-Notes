# Git Guides

## Table of contents

- [Git Configuration](#git-configuration)
- [Status](#status)

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
```

### Git Push to Remote Repo

```text
$ git push origin master
```
