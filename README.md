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
    * [Parla: HPC tasks for shared-memory heterogeneous nodes in Python](slides/Parla.pdf) (Mattan Erez)
    * [PyCOMPSs support to HPC + AI workflows](slides/PyCOMPSs.pdf) (Rosa M. Badia)
    * [PyKokkos: A Performance Portability Framework for Python](slides/PyKokkos.pdf) (Milos Gligoric)
    * [Distributed Tasking in Python with Legion](slides/Legion.pdf) (Elliott Slaughter)
    * [cuPyNumeric, Zero code change scaling of NumPy code](slides/cuPyNumeric.pdf) (Manolis Papadakis)
* Discussion (Q&A)


### Frameworks for HPC Python development

Below is an incomplete list of framework for developing HPC
applications in Python and brief descriptions.

* [Arkouda](https://arkouda-www.github.io/) - A numpy/pandas inspired Python library backed by [Chapel](https://chapel-lang.org/)
* [Charm4py](https://charm4py.readthedocs.io) - Charm++ programming model in Python
* [CuPy](https://cupy.dev) - NumPy/SciPy-compatible Array Library for GPU-accelerated Computing with Python
* [cuPyNumeric](https://developer.nvidia.com/cupynumeric) - Write NumPy, run automatically on clusters of CPUs and GPUs
* [Dask](https://www.dask.org) - Easy parallel Python that does what you need
* [DaCe](https://github.com/spcl/dace) - Data Centric Parallel Programming
* [FlexFlow](https://flexflow.ai) - Drop-in PyTorch, Keras, ONNX interface
* [lbmpy](https://pypi.org/project/lbmpy) - Run fast fluid simulations based on the lattice Boltzmann method in Python on CPUs and GPUs
* [loopy](https://documen.tician.de/loopy) - A code generator for array-based code in the OpenCL/CUDA execution model
* [mpi4py](https://mpi4py.readthedocs.io) - MPI for Python
* [Numba](https://numba.pydata.org) - JIT compiler that translates a subset of Python and NumPy code into fast machine code
* [Pallas](https://jax.readthedocs.io/en/latest/pallas/index.html) - An extension to JAX that enables writing custom kernels for GPU and TPU
* [Parla](https://github.com/ut-parla/Parla.py) - A task-parallel programming library for Python
* [Parsl](https://parsl-project.org) - Productive parallel programming in Python
* [PyCOMPS](https://docs.idmod.org/projects/pycomps/en/latest) - Workflow orchestration in Python
* [PyCUDA](https://documen.tician.de/pycuda) - Pythonic access to Nvidia's CUDA parallel computation API
* [Pygion](https://legion.stanford.edu/pygion) - A task-based framework for Python based on the Legion programming system
* [PyKokkos](https://github.com/kokkos/pykokkos) - Framework for writing performance portable HPC kernels in Python
* [PyOMP](https://github.com/Python-for-HPC/PyOMP) - OpenMP for Python in Numba for CPU/GPU parallel programming
* [PyOpenCL](https://developer.nvidia.com/pyopencl) - Lets you access GPUs and other massively parallel compute devices from Python
* [pystencils](https://pypi.org/project/pystencils) - Run blazingly fast stencil codes on numpy arrays
* [PyTorch](https://pytorch.org) - An open-source machine learning library based on the Torch library
* [Ray](https://www.ray.io) - AI Compute Engine
* [Taichi Lang](https://github.com/taichi-dev/taichi) - Imperative, parallel programming language for high-performance numerical computation

### Contact

If you would like to make any addition, feel free to create a PR with
suggested changes or email Milos Gligoric <gligoric@utexas.edu>.
