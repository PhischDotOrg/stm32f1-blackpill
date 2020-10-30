# stm32f1-blackpill
"Hello World"-like Example for a STM32F1 "Black Pill" Board using an STM32F104 µC.

Some Documentation on the Board: [https://stm32-base.org/boards/STM32F103C8T6-Black-Pill.html](https://stm32-base.org/boards/STM32F103C8T6-Black-Pill.html)

# How to check out
This project makes use of git's [submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) feature. This repository is therefore more of a front-end for other code parts. In order to obtain all the needed code, please check out with the `--recursive` flag.

Example:

```
$ git clone git@github.com:PhischDotOrg/stm32f1-blackpill.git --recursive
```

In case you forgot the `--recursive` flag, run this after check out:

```
$ git submodule update --init --recursive
```

This will initialize, update and download all required submodules. 

# How to build
See the documentation for the common reposority at [https://github.com/PhischDotOrg/stm32-common](https://github.com/PhischDotOrg/stm32-common).
