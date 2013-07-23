Laptop
======

Laptop is a script to set up a Mac OS X laptop for Rails development and general awesomeness.
It is designed to run on a fresh install of OS X 10.8.x, but probably works on 10.7.x.

Requirements
------------

1) Install a C compiler.

Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action)
for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).

Install
-------

1) Clone the repo locally:

    git clone git@github.com:dustMason/laptop.git

2) Read, then run the script:

    laptop/mac

What it sets up
---------------

* Homebrew for managing operating system libraries
* Rbenv for managing versions of Ruby
* Ruby Build for installing Rubies
* Builds Ruby 2.0.0-p247 from source
* Several Ruby gems:
  - Foreman for serving Rails apps locally
  - Bundler for managing Ruby libraries
  - Postgres for talking to Postgres from Ruby
  - Rails for writing web applications
* Latest release of Python 2.7, along with pip
* Latest version of vim
* Exuberant Ctags for indexing files for vim tab completion
* My awesome dotfiles repo which includes:
  - A simple but fully-featured vim config with plugins managed by vundle
  - antigen for managing oh-my-zsh themes and plugins
* Redis for storing key-value data
* Heroku Toolbelt for interacting with the Heroku API
* Heroku Config plugin for local `ENV` variables
* ImageMagick for cropping and resizing images
* The Silver Searcher for finding things in files
* Lots of mac apps:
  - Google Chrome
  - Alfred
  - Caffeine
  - Cyberduck
  - Dropbox
  - gfxCardStatus
  - GitHub
  - iStat Menus
  - iStumbler
  - MPlayerX
  - 1Password
  - Postgres
  - Sequel Pro
  - Skype
  - Sparrow
  - Spectacle
  - XLD

Credits
-------

![thoughtbot](http://thoughtbot.com/assets/tm/logo.png)

Laptop is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community).
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

Thank you, [contributors](https://github.com/thoughtbot/laptop/graphs/contributors)!

License
-------

Laptop is © 2011-2013 thoughtbot, inc. It is free software, and may be
redistributed under the terms specified in the LICENSE file.
