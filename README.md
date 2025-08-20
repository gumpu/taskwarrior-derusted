## About

This is a fork of
[Taskwarrior](https://github.com/GothenburgBitFactory/taskwarrior/) with with
the 3.0 code removed.  It is for my own purposed as I don't use syncing and do
not like the additional dependence on Rust.

## Installing

To install from source requires:

* git
* cmake
* make
* C++ compiler, currently gcc 7.1+ or clang 5.0+ for full C++17 support
* libuuid
* GnuTLS (optional, required for sync)

Clone this repository:

    $ git clone --recursive -b stable https://github.com/GothenburgBitFactory/taskwarrior.git
    $ cd taskwarrior

Then build:

    $ cmake -DCMAKE_BUILD_TYPE=release .
    ...
    $ make
    ...
    [$ make test]
    ...
    $ sudo make install

