portable-environment
====================

A portable and scalable unix environment

This is a lightweight utility that I have developed to help setup my portable unix environment.  The goal was to develop a structured framework that allows for simple and reproducable transfering of my unix environment.  

### To Use:

1. Put this repository in $HOME/p/ or anywhere else (i.e. $HOME/src/).

2. Run the setup script

`$HOME/p/setup/setup`

Your existing "dot-files" will be moved to $HOME/old_dot_files

3.  Move any settings from your old_dot_files to the appropriate environment scope inside $CONF/...

### Further documentation
For now, I suggest you read http://furius.ca/projects/doc/conf.html
