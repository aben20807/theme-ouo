# theme-ouo

+ A Oh My Fish theme inspired by [pure](https://github.com/rafaelrinaldi/pure).
+ pure [![Fish Shell Version](https://img.shields.io/badge/fish-v2.5.0-007EC7.svg?style=flat-square)](http://fishshell.com) [![Build Status][travis-badge]][travis-link]
+ Port of the [`pure`](https://github.com/sindresorhus/pure) ZSH theme to Fish 🐟

<p align=center>
  <img width=585 src=https://imgur.com/8C4hOXn.png>
</p>

## Install and Set theme

### Install [Fish](https://github.com/fish-shell/fish-shell)

```bash
$ sudo apt-add-repository ppa:fish-shell/release-2
$ sudo apt update
$ sudo apt install fish
```

### Install [Oh My Fish!](https://github.com/oh-my-fish)

```bash
$ curl -L https://get.oh-my.fish | fish
```

### Install ouo theme

```fish
$ omf install https://github.com/aben20807/theme-ouo
$ omf theme ouo
```

+ [How to set fish as default shell in Cygwin](https://stackoverflow.com/a/34683320/6734174)

## Update

### [Oh My Fish!](https://github.com/oh-my-fish)

```fish
$ omf u ouo
```

## Features

* Display current directory tail
* Display Git branch name
* Display whether or not the working copy is dirty
* Display ⇡ if there are stuff to be pushed
* Display ⇣ if there are stuff to be pulled
* Display the current folder and command when a process is running
* Display prompt symbol in red if previous command has failed

## License

MIT © [Rafael Rinaldi](http://rinaldi.io)

[travis-link]: https://travis-ci.org/rafaelrinaldi/pure
[travis-badge]: https://img.shields.io/travis/rafaelrinaldi/pure.svg
