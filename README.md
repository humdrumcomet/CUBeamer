# CUBeamerTheme - A Carleton University Beamer Theme
## Introduction

## Warnings
This code is experimental, and has so far only been tested on a linux system (though I suspect it
will work without too much effort on any unix based system).

## Requirements

## Installation
To install this package manually, first make sure that you have a local texmf directory with a
subdirectory named tex. You can do this with the following command, which will create the needed 
directories in your home directory. 

`
$ mkdir -p ~/texmf/tex/
`

This gives the system tex a specific place to look for the package.

Next, using bash (or similar shell) navigate into a folder you plan on storing the luaHelper
package (DO NOT clone into the texmf folder. This will significantly slow down all latex compilations 
as KSPE will try to traverse the .git directory) execut the following commands:

```
$ git clone https://github.com/humdrumcomet/cuBeamerTheme
$ cd cuBeamerTheme
$ ln -s "$PWD/beamertheme-carletonUniversity" ~/texmf/tex/
$ texhash
```

## Basic Usage

The theme can be used by adding the following to the presentation's preamble.

```
\usetheme{carletonUniversity}
```

## To Do's
