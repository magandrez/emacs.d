# emacs.d

## Installation

* Install [Cask](http://cask.readthedocs.io/) using CURL.

`curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python`

* Clone this repository in your home folder

`git clone https://github.com/magandrez/.emacs.d.git`

* Install emacs using [brew](http://brew.sh/) fixing any post install issues if instructed by brew installer.

`brew install --HEAD --with-cocoa --srgb emacs`

* Run `brew linkapps emacs` if you want to start Emacs from Launchpad/Spotlight/Quicksilver.

* Run cask install in `~/.emacs.d/`

`cask install`

* Install ag [the silver searcher](https://github.com/ggreer/the_silver_searcher)

`brew install the_silver_searcher`

Re-start emacs and you should be ready to go.

