+++
title = 'CFS/pythonCFS'
date = 2024-06-17T23:43:18+01:00
draft = false
+++

## About

The Cambridge Electronic Design File System (CFS) is the file format used by the Signal Software Suite to record electrophysiological data, such as data from Transcranial Magnetic Stimulation experiments.

CED distributes a C library to read and write these files. However, this library only compiles on Windows. This library is an attempt to reimplement part of CED's CFS library using only platform-agnostic code compliant with the C standard. Some outdated features will be dropped, such as support for MS-DOS, or near/far pointers for 16-bit segmented memory architectures

I have also written a [python wrapper](https://github.com/m0ose01/pythonCFS) for the library, which is significantly easier to work with.

## Installation

The easiest way to use this library is by installing the python wrapper via pip. See <https://github.com/m0ose01/pythonCFS>.

If you would like to use the original C library, e.g., for use in another language, you can find instructions on how to do so at <https://github.com/m0ose01/CFS>.
