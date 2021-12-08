# gitignore
A collection of .gitignore templates.

This project contains an example of a global gitignore file.

The content of this file has been heavily inspired by the official [Github's collection](https://github.com/github/gitignore).

## Add the global gitignore for all the git repositories
```bash
$ mv Global.gitignore .gitignore_global
$ git config --global core.excludesfile ~/.gitignore_global
```
