---
course_id: 18-369-mathematical-methods-in-nanophotonics-spring-2008
layout: course_section
menu:
  leftnav:
    identifier: 8a05e28adff2283bc695314f6fb1fe70
    name: Tools
    weight: 70
title: Tools
type: course
uid: 8a05e28adff2283bc695314f6fb1fe70

---

Software used in this Course
----------------------------

### The MIT Photonic-Bands (MPB)

The MPB package is a free program for computing the band structures (dispersion relations) and electromagnetic modes of periodic dielectric structures, on both serial and parallel computers. It was developed by Prof. Steven G. Johnson at MIT.

This program computes definite-frequency eigenstates of Maxwell's equations in periodic dielectric structures for arbitrary wavevectors, using fully-vectorial and three-dimensional methods. It is especially designed for the study of photonic crystals (a.k.a. photonic band-gap materials), but is also applicable to many other problems in optics, such as waveguides and resonator systems. (For example, it can solve for the modes of waveguides with arbitrary cross-sections.)

For more information on MPB, see the [MPB home page](http://ab-initio.mit.edu/wiki/index.php/MIT_Photonic_Bands) and the [MPB manual](http://ab-initio.mit.edu/wiki/index.php/MPB_manual). Hopefully, you shouldn't need to know much Scheme (just think of it as a file format with lots of parentheses), but see these [Guile and Scheme links](http://ab-initio.mit.edu/wiki/index.php/Guile_and_Scheme_links) (GNU Guile is the Scheme implementation used in MPB).

For additional help on the use of MPB, read the MPB Demo ([PDF]({{< baseurl >}}/sections/tools/mpb_demo))

The demo uses the files 2dwaveguide.ctl ([CTL](/courses/mathematics/18-369-mathematical-methods-in-nanophotonics-spring-2008/assignments/2dwaveguide.ctl)) and 2dwaveguide-periodic.ctl ([CTL](/courses/mathematics/18-369-mathematical-methods-in-nanophotonics-spring-2008/assignments/2dwaveguideperiodic.ctl))

### Harminv

Harminv is a free program (and accompanying library) to solve the problem of harmonic inversion - given a discrete-time, finite-length signal that consists of a sum of finitely-many sinusoids (possibly exponentially decaying) in a given bandwidth, it determines the frequencies, decay constants, amplitudes, and phases of those sinusoids.

You can use the harminv program to compute resonant frequencies and loss rates from time-domain simulation, using filter-diagonalization methods (FDM) in the Fourier basis as discussed in Lecture 18.

See [harminv](http://ab-initio.mit.edu/wiki/index.php/Harminv) for more information and to download this program.

### Meep

Meep is a free finite-difference time-domain (FDTD) simulation software package developed at MIT to model electromagnetic systems.

To download Meep and for additional information, see the [Meep Web site](http://ab-initio.mit.edu/wiki/index.php/Meep).