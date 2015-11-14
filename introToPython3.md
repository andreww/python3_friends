# Making Friends With Python 3

## Intro

This lesson is targeted at Software Carpentry instructors looking to make the jump from Python 2 to 3 both in their teaching, and in their personal practice. We're hoping to deliver this as a live session at the [Software and Data Carpentry Instructor and Helper Retreat](http://swcarpentry.github.io/instructor-retreat-2015/) on November 14, 2015, and preserve this lesson for future async use by the community. This lesson is just an outline at the moment; pull requests with more ideas and more fleshed out content very welcome, or join the dicussion in [this issue](https://github.com/swcarpentry/instructor-retreat-2015/issues/28).

## 1. Syntactic & Structural Changes

 - `print` / `print()`
 - relative imports
 - strings v's binary data 
 - division

A starting point may be to watch the overview talk by Dave Jones

[![Making friends with Python 3](http://img.youtube.com/vi/r8lOHB9ma8I/0.jpg)]
(http://www.youtube.com/watch?v=r8lOHB9ma8I "Making friends with Python 3")

or the [slides](http://www.waveform.org.uk/presentations/py3friends/)

## 2. Installation
If you don't already have python installed the instructions we provide to learners
now gives you a version of python 3.4 via anaconda. However, it is likly that you
will have previously taught using python 2.7, or will have your own software that
relies on python 2.7. In this case it is useful to be able to run and maintain 
python 2.7 and 3.4 on the same machine.

If you already have anaconda and python 2.7 installed you can add python3 as a new
environment with the command `conda create -n python3 python=3.4 anaconda`. This
installs python 3.4 alongside whatever you already have installed. In order to 
switch from python 2.7 to python 3.4 you can then run `source activate python3`.
Anything installed after this point is part of the "python3" environment. To drop
out of this environemnt and return to your default setup run `source deactive`.
The current environment is local to the particular shell and the command under 
Windows drops `source`.

## 3. Migrating Your Work

 - `2to3` demo
 - `future` module
 - pitfalls
 - the existance of a [porting guide](https://docs.python.org/3/howto/pyporting.html)

## 4. Common Gotchas

 - teaching: what new misconceptions arise for student in 3 compared to 2?
 - anything new and different about notebooks?

## 5. Further Reading

 - where to dig into gory details
