# Hello World (C++20)

This project demonstrates coroutines in C++20.

Linux distro "Pop!_OS 20.10"

cmake version 3.16.3

Ubuntu clang version 11.0.0-2

## Steps

cd build

./doCmake.sh

make VERBOSE=1

./simple-coroutine

## History

dates: June 29, 2021

duration: 2 hours

### Code from Another Developer

This code comes entirely from David Mazières at Stanford.

[Coroutines](https://www.scs.stanford.edu/~dm/blog/c++-coroutines.html)

Except for 2 very important changes to get it to compile with clang (see below).

### Help at the Final Hour

The clang 11 compiler is halfway between experimental and full support for coroutines.

Thanks a bunch to Peter Würtz for providing the particular syntax that got me over the halfway point roadblock.

[Bypass GCC coroutine guards](https://bugreports.qt.io/browse/QTCREATORBUG-24634?gerritReviewStatus=Open)

And thanks to Mysterious Chris for the function that fixed the last compiler error.

[ReturnObject must conform to interface](https://stackoverflow.com/questions/67306337/a-coroutines-promise-must-declare-either-return-value-or-return-void-erro)





