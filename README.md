## About

This is a fork of
[Taskwarrior](https://github.com/GothenburgBitFactory/taskwarrior/) with
all the 3.x code removed.
It is for my own purposed as I don't use syncing and do
not like the additional dependency on Rust.

## Installing

To install from source requires:

* git
* cmake
* make
* C++ compiler, currently gcc 7.1+ or clang 5.0+ for full C++17 support
* libuuid

Clone this repository:

    $ git clone ....
    $ cd taskwarrior

Then build:

    $ cmake -DCMAKE_BUILD_TYPE=release -DCMAKE_INSTALL_PREFIX=$HOME .
    ...
    $ make
    ...
    [$ make test]
    ...
    $ sudo make install

