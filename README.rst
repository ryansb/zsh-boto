====
ZSH-Boto
====

ZSH tab completion for Boto_.

.. _Boto: https://github.com/boto/boto

====
Usage
====

To install::

   $ cd .zsh
   $ git clone git://github.com/ryansb/zsh-boto.git
   $ echo "fpath=($fpath /home/user/.zsh/zsh-boto)
   autoload -uz compinit
   compinit" >> ~/.zshrc

To use::

   lss3 <TAB>
   elbadmin <TAB>
   elbadmin add <TAB>
   elbadmin add myloadbalancer <TAB>
   elbadmin add myloadbalancer i-12345


====
Support
====

Currently supports:

Showing available buckets for lss3 command.

Completing almost all options for elbadmin, including available load balancers.
