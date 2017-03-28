# Sapientiae (wisdom) [![Build Status](https://travis-ci.org/jaylenw/Sapientiae.svg?branch=master)](https://travis-ci.org/jaylenw/Sapientiae)

*Volumen autem sunt et cyphris*, "Book of ones and zeros."  

A book containing various topics in computer science.

# Description

This is a book that I made for myself and others to reference certain topics in computer science.

You can download the latest release of the book as a pdf [here](https://github.com/jaylenw/Sapientiae/releases). You may also visit the live site [here](https://jaylenw.github.io/Sapientiae/).

# Features

* Deploy this book as a website
* Generate a PDF, EPUB, or MOBI file
* Write in Markdown
* Supports MathJax rendering

# Building, Testing, & Development

1. You need to have [Node](https://nodejs.org/en/) and [NPM](https://www.npmjs.com/) installed globally. Assuming you are running Ubuntu 16.04 LTS 64 bit you can run the following commands below:

        sudo apt update  
        sudo apt install nodejs  
        sudo ln -s /usr/bin/nodejs /usr/bin/node  
        sudo apt install npm
        sudo npm install -g npm
        sudo npm install gitbook-cli -g
        sudo apt install calibre
        sudo npm install svgexport -g

2. Clone this repository.

3. In the root of the project run `gitbook install` then `npm install`

4. Run `gitbook serve` and enter the address into your browser the console
has printed. This allows you to preview the book in the web browser.

5. Run `gitbook build` and gitbook will compile a folder with all the web files you need to move to a web server to serve the static files. The directory is called `_book`.

6. To generate a PDF, ePub, or Mobi file, run the respective commands below:

        gitbook pdf ./ ./sapientiae.pdf

        gitbook epub ./ ./sapientiae.epub

        gitbook mobi ./ ./sapientiae.mobi

### Notes

This book is still in its early stages.

Markdown that Gitbook uses is [here](https://toolchain.gitbook.com/syntax/markdown.html).

MathJax website is [here](https://www.mathjax.org/).

-------------------

Pull requests and issues are welcomed.
