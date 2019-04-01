
# Polymake and GAP in Julia

This 1-day course gives an introduction to Julia and on how to use the interfaces to Polymake and GAP from Julia,
using the Julia modules GAP.jl and Polymake.jl developed in the TRR-195.

## General information

The course is meant for beginners in Julia, GAP, and Polymake.
Each session consists of a small lecture and an exercise session,
in which mathematical questions motivated in the lecture will be solved using Julia, GAP, and Polymake.
To participate in the exercises it is necessary that participants bring their own laptop.

To install the latest Julia with GAP and Polymake, please rever to the [installation instructions on the OSCAR website](https://oscar.computeralgebra.de/install/).
Please note that you cannot just install Julia on windows, but it is necessary to use the Ubuntu Subsystem for Windows.
We also recommend to install Jupyter via the Julia commands

    using Pkg
    Pkg.add("IJulia")

to have a notebook interface to Julia.

## Timetable

### 09:00 - 09:45: Helpdesk

If you faced any trouble installing Julia, Polymake, GAP, or Jupyter on your computer, we will help you setting up your computer for the workshop.

### 09:45 - 11:15: Julia

We will cover general things in Julia, as syntax for regular control flow, such as if statements, for loops,
but also handy data structures from Julia's extensive standard library, such as arrays, matrices, hashtables, etc.

### 11:30 - 13:00: GAP in Julia

We will learn about main group theoretical features from GAP, as well as how to access them from Julia.
Topics include conversion of data between Julia and GAP, and accessing GAP features to compute orbits, stabilizer chains, subgroup lattices, etc.

### 16:00 - 17:30: Polymake in Julia

We will learn about how to access Polymake from Julia, as well as how to use some main Polymake features to explore polytopes and cones, such as Hilbert Basis, double description methods, etc.
We will also show how to combine those Polymake features with GAP.jl
