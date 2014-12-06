# Dotfiles

My OSX dotfiles.

## Quick installation:

```
$ cd ~
$ git clone --recursive git@github.com:bradp/dotfiles.git
$ rake
```

## How to use

This repo contains a Rakefile that does some magic things.

``` $ rake ``` - Will overwrite your existing dotfiles and symlink ours to your home directory.

``` $ rake install ``` - Same as 'rake'

``` $ rake setup_file[ .filename .file2 ] ``` - Symlink new files that you've added to the dotfiles/ directory

``` $ rake setup_file[ .filename ] ``` - Symlink a single file that you've added to the dotfiles/ directory


## What it includes

 * **bin/**

 	Miscellaneous scripts. This is also added to your path.
 * **misc**

 	Miscellaneous scripts, that you might not run all the time. Currently includes `setup-new-mac.sh`, which will setup a base install of a new Mac.
 * **zsh-custom/**

 	My custom [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) theme and Oh My Zsh plugins
 * **.maid/**

 	My [Maid](https://github.com/benjaminoakes/maid) rules for cleanup of Desktop, Downloads, and automatic Brew and Oh My Zsh upgrades.

 	* **.vim/**

 	My Vim plugins.

 * **.aliases**

 	Aliases. Gets sourced from inside the dotfiles folder.
 * **.exports**

	Environment exports
 * **.gemrc**

 	Speeds up gem installation
 * **.gitconfig**

 	Make git awesome.
 * **.global_ignore**

 	Our global git ignore.
 * **.hushlogin**

 	Stop the login message when logging into remote servers.
 * **.vimrc**

 	Make your vim the prettiest vim.
 * **.zshrc**

 	The magic that makes Zsh behave amazingly.

