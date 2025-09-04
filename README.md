# debian - laptop

These are my dotfiles.

And

This is an example of using git to store your configuration.

It requires only a single .gitignore file.

A setup bash program is included to install programs.

This is only to install programs.

All configuration state is synced via git.

This is accomplished by initializing a git repository in either, home, or root.

Creating a git ignore file and ignoring ALL.

To save state, add the path of the file you would like to save to the .gitignore file.

You can include entire folder contents using *.

Before including entire folders it is reccommended to check for senstive data.

This is the best way to configure and store custom state.

We end up with things like NIX when people think they are smart.

If you need similar rollback functinality or a package list use a program made for this purpose.

timeshift - rollbacks
Rebos - rollbacks and package management

To enable this functionality uncomment the begining lines in setup.

This process works on any linux distrobution.

The following alias can also be created for any linux distrobution and package manager, and are included in this repository

clean

check

install

remove

update

To use this method in enterprise formats, combine it with the following programs like ansible and include your version of this process.



