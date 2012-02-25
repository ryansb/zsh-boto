====
ZSH-Boto
====

ZSH tab completion for Boto_.

.. _Boto: https://github.com/boto/boto

====
Usage
====

$ cd .zsh
$ git clone git://github.com/ryansb/zsh-boto.git
$ echo "fpath=($fpath /home/user/.zsh/zsh-boto)
autoload -uz compinit
compinit" >> ~/.zshrc

====
Support
====

Currently supports:

Showing available buckets for lss3 command.

Completing almost all options for elbadmin, including available load balancers.
