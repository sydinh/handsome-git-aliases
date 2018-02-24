# Handsome Git Aliases
Git aliases can make your Git experience simpler, easier, and more familiar.

> $ git config --global alias.YourAlias

## Add a Git Alias
`$ git config --global alias.YourAlias EntireCommand`

Example

`$ git config --global alias.hi status`

This means, instead of typing `git status`, you just need to type `git hi`, you will see the results in terminal is the same.

## View all Git Aliases setting
`$ git config --get-regexp alias`

## Edit or Remove Git Aliases
In your terminal, just type:

`$ git config --global --unset alias.YourAlias`

Or

`$ vim ~/.gitconfig` then find alias to edit / remove.

Or

`$ git config --global --edit` then find alias to edit / remove.

## This is my handsome Git Aliases

```
$ git config --global alias.co checkout // branch alias

$ git config --global alias.br branch // branch alias

$ git config --global alias.ci commit // commit alias

$ git config --global alias.st status // status alias

$ git config --global alias.log "log --oneline" // show commit histories in one line

$ git config --global alias.alias "config --get-regexp alias" // show all aliases setting

$ git config --global alias.last "log -1 HEAD" // by this way, you can see the last commit easily

$ git config --global alias.visual "!gitk" // run an external command. I use `$ git visual` instead `gitk`

$ git config --global alias.df diff // diff alias

```

Many thanks to [Git Aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases)