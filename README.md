## Can Python Do for HPC What It Did for Machine Learning?

This repository accopanies a [Birds of a
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
* Discussion (Q&A)


### Frameworks for HPC Python development

Below is an incomplete list of framework for developing HPC
applications in Python.

* [CuPy](https://cupy.dev)
* [Dask](https://www.dask.org)
* [loopy](https://documen.tician.de/loopy)
* [mpi4py](https://mpi4py.readthedocs.io)
* [Numba](https://numba.pydata.org)
* [Parla](https://github.com/ut-parla/Parla.py)
* [Parsl](https://parsl-project.org)
* [PyCUDA](https://documen.tician.de/pycuda)
* [PyKokkos](https://github.com/kokkos/pykokkos)
* [PyOMP](https://github.com/Python-for-HPC/PyOMP)
* [PyOpenCL](https://developer.nvidia.com/pyopencl)
* [PyTorch](https://pytorch.org)
* [Ray](https://www.ray.io)
