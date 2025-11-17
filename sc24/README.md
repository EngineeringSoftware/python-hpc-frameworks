## Can Python Do for HPC What It Did for Machine Learning?

This directory accopanies a [Birds of a
Feather](https://sc24.conference-program.com/presentation/?id=bof213&sess=sess633)
session at Supercomputing Conference 2024.

```
Can Python Do for HPC What It Did for Machine Learning?
Wednesday, 20 November 2024 12:15pm - 1:15pm EST
Location B212
```

### Description

Python is now one of the most popular programming languages. In HPC,
it has predominantly been used to coordinate coarse-grain library
components or workflows. However, it is increasingly being used to
develop and coordinate applications with dynamic finer-grain
components that are challenging to map efficiently onto heterogeneous
resources. In this BoF, we discuss this challenge and efforts to
design Python-based HPC, production quality codes for HPC leadership
platforms. We will discuss issues such as multithreading, GPU kernel
development, task-based coordination on heterogeneous systems with a
mix of CPUs and GPUs, inter-node interoperability, scalability,
portability, and reproducibility.


### Program

* Introduction
* Lightening talks
    * [Parla: HPC tasks for shared-memory heterogeneous nodes in Python](slides/Parla.pdf) (Mattan Erez)
    * [PyCOMPSs support to HPC + AI workflows](slides/PyCOMPSs.pdf) (Rosa M. Badia)
    * [PyKokkos: A Performance Portability Framework for Python](slides/PyKokkos.pdf) (Milos Gligoric)
    * [Distributed Tasking in Python with Legion](slides/Legion.pdf) (Elliott Slaughter)
    * [cuPyNumeric, Zero code change scaling of NumPy code](slides/cuPyNumeric.pdf) (Manolis Papadakis)
* Discussion (Q&A)
