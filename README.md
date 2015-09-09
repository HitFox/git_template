git template
=========================

This repo contains helpful [git hooks][git_docs_hooks] that will be copied to the $GIT_DIR of a project 
after it is created.

See [git template][git_docs_template] for documentation.


Install
----------------------
Clone repo to your $HOME. You could also choose another folder for the git template.
```bash
git clone git@github.com:kr1sp1n/git_template.git ~/.git_template
```


Configure
----------------------

```bash
git config --global init.templatedir '~/.git_template'
```
After that new repos created with either `git clone` or `git init` will have the files
and directories that are in this template repo.


Update
----------------------
If the template changed after creating a repository, you can simply run `git init` 
inside that repository again and it will pick up the new template.
Be aware that only files and directories get copied that are not already present in your .git folder of 
your project.



[git_docs_hooks]: http://www.git-scm.com/book/en/v2/Customizing-Git-Git-Hooks
[git_docs_template]: http://www.git-scm.com/docs/git-init#_template_directory
