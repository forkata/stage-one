# Stage-One

This is a shell script to setup a box for development.

This was inspired and uses parts of the [Laptop](https://github.com/thoughtbot/laptop) script
made by the awesome people at [Thoughtbot](https://robots.thoughtbot.com/).

A lot of the shell-fu that is used in this script is stolen from the above mentioned script!

## Requirements

This script currently has only one version which works on:

* OS X
  * using the awesome [Homebrew](http://brew.sh/) package manager
  * and [Cask](http://caskroom.io/) for larger binaries

## Install

```sh
curl --remote-name https://raw.githubusercontent.com/forkata/stage-one/master/brew
less brew
sh brew 2>&1 | tee ~/stage-one.brew.log
```
