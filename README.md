# Git Basics

The presentation takes you through the basics. Here's some other suggestions and resources.

## Setup Suggestions

### Config

Set up git to know your name and email address. (The `--global` flag sets these as the default settings for your user, stored in `~/.gitconfig`. They can be locally overridden in individual repositories.)

```
git config --global user.name "Clara Bennett"
git config --global user.email "clara@picwell.com"
```

If you are not familiar with vim, consider setting your git editor to nano, which has a simple interface.

```
git config --global core.editor nano
```

Explicitly set the push default to "simple", to silence the warning that will keep popping up

```
git config --global push.default simple
```

### Aliases

```
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.unstage "reset HEAD --"
```

## Tools for Improved Git Workflow

- [Put the current git branch in your bash prompt](http://code-worrier.com/blog/git-branch-in-bash-prompt/), or [switch to oh-my-zsh and enable the git plugin](https://github.com/robbyrussell/oh-my-zsh).
- Use the [SublimeText package manager](https://packagecontrol.io/installation#st2) to install [Git Gutter](https://github.com/jisaacks/GitGutter). It subtly highlights modified code (relative to the checked-out commit) in your SublimeText editor.
- Use [SourceTree](http://www.sourcetreeapp.com/) to help you visualize and navigate your git repos, and for all of the obscure commands you can never remember.

## Other Resources

- Try this [git branching game](http://pcottle.github.io/learnGitBranching/) to get a better feel for git mechanics and learn some more advanced features.
- Download [Pro Git](http://git-scm.com/book/en/v2) (free book!). Chapter 2: Git Basics and Chapter 3: Git Branching contain most everything you need to be an effective git user.
