# WinPorts

## About
This is a BSD-like collection of software to compile on Windows

## Why another Windows package manager? 
A big effort of the GNU project consists in porting open source software to
  Windows; not in order to support Windows, but to empower people to move to
  open source operating systems. Now, there are already a few Windows package
  managers like scoop and nuget. And besides, compiling from source is so slow!
  So why the heck putting in all the effort to create yet another Windows
  package manager?

  It's no secret that open source software which functions well on Linux isn't
  as meticuously maintained on Windows. But in order to find the remaining
  faults, it's imperative that the software is compiled from source and that the
  process of compiling is reproducible. 

## Technical Overview
WinPorts starts with Mingw-64, which includes all the development tools one is
used to on Linux. But contrary to pacman (a very useful package manager
nonetheless) which installs binary packages, we include the build scripts (many
of them autotools-based) to make the process of compiling the software
reproducible.

Based on a personal need, the first software to be compiled will be Emacs and
it's dependencies. 






