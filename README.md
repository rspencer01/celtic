Celtic Knots
============

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

A quick utility for rendering celtic knots.  Usage is mostly explained by the `--help` flags, or a brief browse of the code.  Check out the samples too.

Sample images
-------------
These are all hand designed.

<img src="samples/IMO_logo.png" width="400px">

<img src="samples/5x7.png" width="400px">

<img src="samples/weave.png" width="400px">

<img src="samples/kells.png" width="400px">

<img src="samples/long_weave.png" width="800px">

Example input file
------------------
These can be seen in the sample folder.  Here is the input file for the first image above
~~~
2 2
xx
xx
x-x
|x|
x-x
~~~

Procedural Braids
-----------------
Long, thin knots (useful for borders etc) can be generated with the `generate_braid` program.  Here are some samples of various sizes.

<img src="samples/braid1.png" width="400px">

<img src="samples/braid2.png" width="400px">

<img src="samples/braid3.png" width="400px">

<img src="samples/braid4.png" width="400px">

How to Use
----------
Usage is very simple, but to get started try running
~~~
python celtic samples/5x7.spec
~~~
and viewing `knot.png`.

For braids like the above, use (on linux/OSX)
~~~
./generate_braid | ./celtic
~~~
Use the `--help` flag for more options.
