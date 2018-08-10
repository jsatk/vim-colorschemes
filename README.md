**NOTE:** This is my personal fork of [Franco][flazz]'s colorschemes plugin.  At some point `colors/darkBlue.vim` was renamed to `colors/darkblue.vim` incorrect and it causes macOS & git to throw a fit every time I update my plugins.  So I forked it and forced a rename and called it a day.  If that's all you're looking to do — to stop your Vim plugin manager from yelling at you every time you update all plugins then you can use this fork instead.  But I prolly won't be maintaining it and if [Franco][flazz] ever fixes the issue in the main repo I'll prolly close this fork.  If you're using this and then one day it doesn't exist it means Franco fixed the git rename issue in the main repo and you can move back to that.

---

[flazz]: https://github.com/flazz

**me:** Hi everyone, my name is Franco and I'm addicted to colorschemes

**everyone else:** *Hi Franco*

Vim colorschemes
================

one stop shop for vim colorschemes.

this was [originally] harvested from vim.org. only colorschemes downloaded in a single `.vim`
file are included.

for hacking on vim.org harvesting see the branch [prep](https://github.com/flazz/vim-colorschemes/tree/prep).

Policy
------
- honor system is in effect!
- new schemes are welcome!
- upstream updates are accepted!
- non-upstream updates are accepted as derivitive schemes: pick a new filename; cite the original!
- housekeeping updates are accepted too!

Installation
------------

Basic install - very simple (*nix or cygwin install)

    mkdir ~/.vim
    git clone https://github.com/flazz/vim-colorschemes.git ~/.vim

if you [use vim + pathogen](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/)

    cd ~/.vim
    git submodule add https://github.com/flazz/vim-colorschemes.git bundle/colorschemes

if you [use vim + vundle](https://github.com/gmarik/vundle)

    " add to .vimrc
    Plugin 'flazz/vim-colorschemes'
    :PluginInstall

if you aren't so clever just get all the files in `colors/*.vim` into
  `~/.vim/colors`

    # after downloading; unpacking; cd'ing
    cp colors/* ~/.vim/colors
    
Using
-----

To change the colorscheme of Vim, add to your `.vimrc`:

    colorscheme nameofcolorscheme
    
For example, to change the color scheme to wombat:
    
    colorscheme wombat
    
To change to Molokai:

    colorscheme molokai
    
Inside Vim, you use:
    
    :colorscheme molokai

Previewing colorschemes
-----------------------
There are quite a few colorschemes in this. To preview them on your live code inside of Vim, checkout [this page from the vim wikia](http://vim.wikia.com/wiki/Switch_color_schemes) and [this repo for easy installation](https://github.com/felixhummel/setcolors.vim).


Something missing? Fork!
------------------------

fork [this repo](http://github.com/flazz/vim-colorschemes); send a
pull request!; I'll take it!

- - -

I'm a slave to aesthetics. If you are too, I hope this helps.

[email](mailto:flazzarino@gmail.com)
