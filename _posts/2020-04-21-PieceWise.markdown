---
layout: post
title: Piecewise Interpolation
date: 2020-04-21
description: Description and code for the Piecewise Interpolation Project. # Add post description (optional)
img: Bezier-vs-piecewise-linear-interpolation-of-four-points.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [C++, Piecewise Interpolation]
---
<blockquote>

<h2>Least Squares Approximation C++</h2>

<p>
 Least Squares Approximation will take an input file of CPU core temperature values and perform both a linear piecewise interpolation as well as a global linear approximation. Written in C++.
</p>
<p> 
<h3>Requirements</h3>

g++ v5.4 or newer
Make

Compilation

The code can be compiled with the provided makefile using the standard make command.

If compiling the code manually, or integrating into a larger program, include the following flags:

FLAGS=-std=c++11 -fsanitize=address -fuse-ld=gold -Wall -MMD
Note that flag -fuse-ld=gold is only required on certain Ubuntu systems due to a known bug with g++ 5.x.
</p>
<p> 
	Sample Execution & Output

If program is run without command line arguments, using

./leastSquares
the following message will be displayed.
</p>
<p> 
Insufficient data.
Usage: ./leastSquares <filename>
Please note that the program will accept an input file that contains only integers. If there are any other characters besides integers, the program will not run.

If run using

./leastSquares sensors-2018.12.26-no-labels.txt
</p>
<p> 
output similar to

0 <= x <= 30; y_0 = 61.0000 + 0.6333x; interpolation
30 <= x <= 60; y_1 = 98.0000 + -0.6000x; interpolation
60 <= x <= 90; y_2 = 20.0000 + 0.7000x; interpolation
...
will be provided in an accompanying .txt file labeled: sensors-2018.12.26-no-labels.txt-core{#}.txt. Note that the precision estimates will vary by architecture/system.
</p>
</blockquote>

<button name="Get Code" onclick=https://www.google.com> GitHub </button>

