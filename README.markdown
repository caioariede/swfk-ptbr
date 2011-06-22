Snake Wrangling for Kids Book Contents
======================================

"Snake Wrangling for Kids" is a printable electronic book, for children 8 years and older, who would like to learn computer programming. It covers the very basics of programming, and uses the Python 3 programming language to teach the concepts.

There are 3 different versions of the book (one for Mac, one for Linux and one for Windows). There have been around 19,000 downloads, as of September 2009.

The Book Source
===============

LaTeX source of "Snake Wrangling for Kids"

This work is licensed under the Creative Commons Attribution-Noncommercial-Share Alike 3.0 New Zealand License.
To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/3.0/nz or send a letter to Creative Commons, 171 Second Street, Suite 300, San Francisco, California, 94105, USA.

The original version written by Jason R Briggs in english can be found at http://code.google.com/p/swfk/

Building from Source
====================

To build, you'll need latex, and dvipdf.

Run the following command to build:

    python setup.py build

On MacOSX, you can use [BasicTeX](http://www.tug.org/mactex/morepackages.html), but you must execute the following commands *before* building the source.

    sudo tlmgr update --self
    sudo tlmgr install textpos wrapfig
