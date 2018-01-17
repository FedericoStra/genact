# genact - a nonsense activity generator

[![Build Status](https://travis-ci.org/svenstaro/genact.svg?branch=master)](https://travis-ci.org/svenstaro/genact)
[![license](http://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/svenstaro/genact/blob/master/LICENSE)

## Installation

You don't have to isntall anything! For your convenience, prebuilt binaries for Linux, OSX and Windows are provided [here](https://github.com/svenstaro/genact/releases) that should run without any dependencies. **Additionally, there is a web version at https://svenstaro.github.io/genact/**

It's compatible with Linux, OSX, Windows 10 (it needs a recent Windows 10 to get ANSI support) and most modern web browsers.

## Compiling

Just clone it like usual and `cargo run` to get output:

    git clone https://github.com/svenstaro/genact.git
    cd genact
    cargo run

You can do this using any Rust version.

## Running

To see a list of all avilable options, you can run

    ./genact -h

In the web version, you can run specific modules by providing them as `?module`
parameters like this:

    http://svenstaro.github.io/genact?module=cc&module=memdump