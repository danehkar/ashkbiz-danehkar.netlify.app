---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'MPI_XSTAR: MPI-based Parallelization of the XSTAR Photoionization Program'
subtitle: ''
summary: ''
authors:
- Ashkbiz Danehkar
- Michael A. Nowak
- Julia C. Lee
- Randall K. Smith
tags:
- '"Astrophysics - High Energy Astrophysical Phenomena"'
- '"Astrophysics - Instrumentation and Methods for Astrophysics"'
- '"Computer Science - Distributed"'
- '"Parallel"'
- '"and Cluster Computing"'
categories: []
date: '2018-02-01'
lastmod: 2021-02-18T15:40:20-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-02-18T20:40:20.436290Z'
publication_types:
- '2'
abstract: We describe a program for the parallel implementation of multiple runs of
  XSTAR, a photoionization code that is used to predict the physical properties of
  an ionized gas from its emission and/or absorption lines. The parallelization program,
  called MPI_XSTAR, has been developed and implemented in the C++ language by using
  the Message Passing Interface (MPI) protocol, a conventional standard of parallel
  computing. We have benchmarked parallel multiprocessing executions of XSTAR, using
  MPI_XSTAR, against a serial execution of XSTAR, in terms of the parallelization
  speedup and the computing resource efficiency. Our experience indicates that the
  parallel execution runs significantly faster than the serial execution, however,
  the efficiency in terms of the computing resource usage decreases with increasing
  the number of processors used in the parallel computing.
publication: '*pasp*'
doi: 10.1088/1538-3873/aa9dff
---
