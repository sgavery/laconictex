laconictex
==========

A simple python script that filters LaTeX output to only the
interesting parts. Uses linux `stdbuf` command to line buffer output;
colors output according using python package `termcolor` if available.

Basic usage:
```
$ laconictex file.tex
```

Use
```
$ laconictex --help
```
for help.
