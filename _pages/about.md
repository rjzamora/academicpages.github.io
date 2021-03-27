---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Senior Systems Software Engineer on the [RAPIDS](https://rapids.ai/) team at NVIDIA.  Most of my work is focused on the development of parallel algorithms for distributed IO and ETL (especially for systems with multiple GPUs). I contribute heavily to both [Dask-Dataframe](https://docs.dask.org/en/latest/dataframe.html) and Dask-CuDF, where I have been responsible for many improvements to the IO, shuffling, and join APIs. I also personally implemented the Multi-GPU NVTabular POC introduced at [GTC 2020](https://www.youtube.com/watch?v=zWe02O2po1U), and am now spearheading the ongoing development of parallel feature-engineering operations for recommender-system applications.

Most of my recent software contributions can be found in the following libraries:

- **Dask**: A flexible parallel-computing library for Python ([repo](https://github.com/dask/dask))
- **CuDF & Dask-CuDF**: A Pandas-like API for GPU-accelerated DataFrames ([repo](https://github.com/rapidsai/cudf))
- **NVTabular**: A feature engineering and preprocessing library for tabular data ([repo](https://github.com/NVIDIA/NVTabular), [blog](https://medium.com/rapids-ai/nvtabular-all-in-on-dask-6241b4e9ca19))
- **PyNVML**: A Python interface to GPU management and monitoring utilities ([repo](https://github.com/gpuopenanalytics/pynvml))
- **NVDashboard**: A JupyterLab extension for displaying GPU dashboards ([repo](https://github.com/rapidsai/jupyterlab-nvdashboard), [blog](https://medium.com/rapids-ai/gpu-dashboards-in-jupyter-lab-757b17aae1d5))


**Previous (Research) Experience**

Before joining NVIDIA, I worked in the ALCF Data Science group at Argonne National Laboratory (January 2018 - April 2019). My research was focused on the development of parallel I/O algorithms, and software, for extreme-scale computing.  Some notable projects include:

- ExaHDF5: An IO/HDF5-Focused Project within the DOE Exascale Computing Project (ECP)
  - Custom-Collective IO in MPICH/HDF5 ([repo](https://xgitlab.cels.anl.gov/ExaHDF5/BuildAndTest/-/blob/master/CCIO_Documentation/ccio_overview.md))
  - NetCDF HDF5 VOL ([repro](https://xgitlab.cels.anl.gov/ExaHDF5/pnetcdf_vol))
  - Lustre Optimizations for MPI-IO and HDF5 ([repro](https://www.opensfs.org/wp-content/uploads/2018/04/Tessier-Theta_Lustre_Performance_Investigations.pdf))
- Deep-learning IO acceleration with node-local storage ([ISAAC component](https://xgitlab.cels.anl.gov/ftessier/mpiio-local-storage-wrapper/-/tree/allmap))
- Software Sustainability and Productivity ([blog](https://bssw.io/blog_posts/adopting-continuous-integration-for-long-timescale-materials-simulation))
- HPC/IO Training - Example Talks:
  - [A Brief Introduction to HPC I/O](https://indico.fnal.gov/event/18091/contributions/45649/attachments/28369/35073/HEPIOworkshop-Zamora.pdf)
  - [Parallel I/O and Storage at ALCF](https://www.alcf.anl.gov/support-center/training-assets/parallel-io-and-storage)

Before joining Argonne, I was a postdoctoral researcher (and then staff scientist) in the Theoretical Division at Los Alamos National Laboratory. During my postdoctoral appointment in the *Physics and Chemistry of Materials Group*, I worked under the supervision of Danny Perez and Arthur Voter, the pioneer of the accelerated molecular dynamics (AMD) approach to long-timescale simulations of interacting atoms. Through my wonderful experience at LANL, I had the opportunity to build a unique expertise in the development of parallel methodologies for high-fidelity materials simulation. Some notable work includes:

- Parallel Methods for Accelerated Molecular Dynamics (AMD)
  - SpecTAD: Speculatively-parallel temperature-accelerated dynamics ([repo](https://github.com/lanl/spectad))
  - Initial SpecTAD design/development guided by discrete-event simulation ([paper](https://journals.sagepub.com/doi/abs/10.1177/0037549716674806))
  - TAD/SpecTAD [Review Chapter](https://www.osti.gov/servlets/purl/1329594)
  - TAD/SpecTAD/ParTAD Algorithms [paper](https://www.osti.gov/pages/servlets/purl/1441309)
  - Parallel AMD [Review Chapter](https://link.springer.com/referenceworkentry/10.1007%2F978-3-319-44677-6_25)
- EXAALT: Exascale Atomistics for Accuracy, Length & Time ([repo](https://gitlab.com/exaalt))
- Performance Prediction Toolkit (PPT) ([repo](https://github.com/lanl/PPT))


**Publicly-accessible Repositories**: [Github](https://github.com/rjzamora),  [GitLab](https://gitlab.com/rjzamora), [xGitLab](https://xgitlab.cels.anl.gov/rzamora)