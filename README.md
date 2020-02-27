# Panda Kucha

[Pandoc](https://pandoc.org/) boilerplate for [PechaKucha](https://en.wikipedia.org/wiki/PechaKucha) talks with [reveal.js](https://revealjs.com/).

## Install

Simply clone this repository.

As a convenience, the repository includes reveal.js as a submodule. You can download it when cloning the repository:

    git clone --recursive https://github.com/frederik-elwert/panda-kucha.git

Or, if you cloned the repository without the `--recursive` option, you can download it later:

    git submodule update --init

## Usage

Edit slide content and/or background images as needed, then create HTML slide show like this:

    pandoc -d pk
