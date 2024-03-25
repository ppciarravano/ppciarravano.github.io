---
layout: post
title: "LarmorFluid: PIC/FLIP fluid simulation Solver"
author: "Pier Paolo Ciarravano"
categories: journal
tags: [projects,fluids]
image:
  feature: larmorfluid_id.jpg
  teaser: larmorfluid_id.jpg
  credit:
  creditlink:
---

I have just released on [GitHub](https://github.com/ppciarravano/larmorfluid-yapfs) a first development version of LarmorFluid, another classical implementation of PIC/FLIP fluid simulation solver based on algorithms described in the book “Fluid Simulation for Computer Graphics” by Robert Bridson, but with some particular future goals:

* Use of [OpenVDB](http://www.openvdb.org/) and future implementation using [OpenVDBPoints](https://github.com/dneg/openvdb_points_dev) lib
* NVIDIA CUDA 8 and cuSPARSE API
* Multithread using TBB
* Handling of large grid and large dataset
* Use of [NVIDIA GVDB Sparse Volumes](https://developer.nvidia.com/gvdb)
* Export particles with [Disney Partio](https://www.disneyanimation.com/technology/partio.html) or other formats
* Import from [Alembic](http://www.alembic.io/)
* Unit test using CppUnit
* Availability of AWS EC2 AMI image already configured to run the solver easily on a [AWS EC2 P2 Istances](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/accelerated-computing-instances.html)


The project is still in development and debugging.

<iframe width="700" height="394" src="https://www.youtube.com/embed/jkg3ykTz2xo?rel=0" frameborder="0" allowfullscreen></iframe>
