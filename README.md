<a name="top"></a>

# FoOtS

[![License](https://img.shields.io/badge/license-GNU%20GeneraL%20Public%20License%20v3,%20GPLv3-blue.svg)]()
[![License](https://img.shields.io/badge/license-BSD2-red.svg)]()
[![License](https://img.shields.io/badge/license-BSD3-red.svg)]()
[![License](https://img.shields.io/badge/license-MIT-red.svg)]()

[![Status](https://img.shields.io/badge/status-alpha-orange.svg)]()
[![GitHub issues](https://img.shields.io/github/issues/Fortran-FOSS-Programmers/FoOtS.svg)]()

### FoOtS, Fortran Operating System Library, lightweight binding of GNU C Library 

- FoOtS is a pure Fortran (KISS) lightweight binding of GNU C Library;
- FoOtS is Fortran 2008+ standard compliant;
- FoOtS is OOP designed;
- FoOtS is a Free, Open Source Project.

#### Table of Contents

+ [What is FoOtS?](#what-is-FoOtS?)
+ [Main features](#main-features)
+ [Status](#status)
+ [Copyrights](#copyrights)
+ [Documentation](#documentation)

## What is FoOtS?

Modern Fortran standards (2003+) have introduced support for developing mixed languages Fortran/C codes. Fortran has poor bultin support for low-level Operating System operations (remove files, create/remove directories, etc...). On the contrary, C language has the GNU C Library, the most used low-level library in the Unix world. FoOtS is designed as a KISS and lightweight OOP Fortran binding of the GNU C Library: FoOtS allows Fortran poor people to access (easily) to a **small** (yet useful) subset of GNU C Library functions directly from Fortran without effort. 

Go to [Top](#top)

## Main features

FoOtS is aimed to be a KISS-pure-Fortran (lightweight) binding of the GNU C Library, it being:

+ [ ] Pure Fortran implementation (exploiting `ISO_C_BINDING` module);
+ [ ] KISS and user-friendly:
    + [ ] simple API, based on one OOP object;
    + [ ] easy building and porting on heterogeneous architectures;
+ [ ] lightweight:
    + [ ] files handling:
        + [ ] inquire file type;
        + [ ] create file:
        + [ ] remove file;
    + [ ] directoris handling:
        + [ ] recursive loop trhough directory;
        + [ ] path sanitize;
+ [ ] portable:
    + [ ] POSIX compliant:
+ [ ] well documented:
    + [ ] clear documentation of schemes implementations;
    + [ ] complete API reference;
    + [ ] comprehensive wiki:
+ [x] collaborative developed;
+ [x] FOSS licensed;

Any feature request is welcome.

## Status

FoOtS project is just started.

We are searching for Fortraners enthusiast joining our team.

## Copyrights

FoOtS is an open source project, it is distributed under a multi-licensing system:

+ for FOSS projects:
  - [GPL v3](http://www.gnu.org/licenses/gpl-3.0.html);
+ for closed source/commercial projects:
  - [BSD 2-Clause](http://opensource.org/licenses/BSD-2-Clause);
  - [BSD 3-Clause](http://opensource.org/licenses/BSD-3-Clause);
  - [MIT](http://opensource.org/licenses/MIT).

Anyone is interest to use, to develop or to contribute to FoOtS is welcome, feel free to select the license that best matches your soul!

More details can be found on [wiki](https://github.com/Fortran-FOSS-Programmers/FoOtS/wiki/Copyrights).

Go to [Top](#top)

## Documentation

Besides this README file the FoOtS documentation is contained into its own [wiki](https://github.com/Fortran-FOSS-Programmers/FoOtS/wiki). Detailed documentation of the API is contained into the [GitHub Pages](http://Fortran-FOSS-Programmers.github.io/FoOtS/index.html) that can also be created locally by means of [ford tool](https://github.com/cmacmackin/ford).

Go to [Top](#top)
