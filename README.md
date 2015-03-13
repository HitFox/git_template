git_template
===================

This repo contains files and directories that will be copied to the $GIT_DIR after it is created.


Install
----------------------
Clone repo to your $HOME. You could also choose another folder for the git template.

```bash
git clone git@github.com:HitFox/git_template.git ~/.git_template
```

Configure
----------------------

```bash
git config --global init.templatedir '~/.git_template'
```

After that new repos created with either `git clone` or `git init` will have the files
and directories that are in this template repo.
