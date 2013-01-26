zsh-completions-osx
===================

zsh completion scripts for Mac OS X specific tools.

Installation
------------

* Clone the repository:

        git clone git://github.com/yujinakayama/zsh-completions-osx.git

* Include the directory in your `$fpath`, for example by adding in `~/.zshrc`:

        fpath=(path/to/zsh-completions/src $fpath)

* You may have to force rebuild `zcompdump`:

        rm -f ~/.zcompdump; compinit

Note
----

This `README.md` is based on [zsh-users/zsh-completions](https://github.com/zsh-users/zsh-completions/blob/master/README.md)'s one.
