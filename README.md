# SVD-Loader for Ghidra

[For more information, read our blog post.](https://leveldown.de/blog/svd-loader/)

## Installation

Simply add the checked-out Git repository to your Ghidra-Scripts search paths.

## Usage

The script can be found in the `leveldown security` folder in Ghidra's Script Manager. [More info here.](https://leveldown.de/blog/svd-loader/)

## Getting SVDs

- [cmsis-svd contains over 650 SVDs](https://github.com/posborne/cmsis-svd/)
- [Keil Software Packs](https://www.keil.com/pack)

## Credits

The cmsis-svd code is a fork from Posborne's [cmsis-svd](https://github.com/posborne/cmsis-svd/), ported to work on Ghidra's Jython. Without this library this script could not exist!

## Licensing

The code in `cmsis_svd/` is licensed under the Apache License v2.0, the same as the 'upstream' [cmsis-svd](https://github.com/posborne/cmsis-svd/). The SVD-Loader itself is licensed under GPLv3.
