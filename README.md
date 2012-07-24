Laptop
======

Laptop is a script to set up your Max OS X laptop as a Rails development machine.

Requirements
------------

* A C compiler, such as GCC, LLVM, or Clang.

Download a compiler from [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) if you're on Snow Leopard (OS X 10.6) or [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action) if you're on Lion (OS X 10.7).

* zsh as your login shell.

To change your login shell run this from a Terminal:

    chsh -s /bin/zsh

Install
-------

Run the script:

    zsh < <(curl -s https://raw.github.com/thoughtbot/laptop/master/mac)

What it sets up
---------------

* Homebrew (for managing operating system libraries)
* Qt (used by Capybara Webkit for headless JavaScript testing)
* Ack (for finding things in files)
* ImageMagick (for cropping and resizing images)
* RVM (for managing versions of the Ruby programming language)
* Ruby language (for writing general-purpose code)
* Bundler gem (for managing Ruby libraries)
* Rails gem (for writing web applications)
* Git Remote Branch gem (for faster git branch creation and deletion)

It should take about 30 minutes for everything to install, depending on your machine.
