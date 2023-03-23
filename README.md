## Productivity Frameworks for HPC

Scientific discovery is increasingly enabled by productivity
frameworks not designed for high-performance computing
(HPC). High-level languages such as Python, machine learning
frameworks, and container technologies allow
users to rapidly develop, test, and execute their science algorithms
in a variety of platforms. While great headway has been made to run
these technologies on HPC systems, their portability and performance
can be limited in that the communication libraries they use may not be
a good match for what performs best on the HPC system. 

Productivity frameworks for HPC includes container recipes, build
recipes, continuous integration scripts, and other software aimed at
testing the portability of containerized HPC software across platforms
and interconnects. In particular, it tests the utility of
bind-mounting at the MPI layer (rather than the underlying fabric
layer) to leverage a standardized protocol and avoid various technical
debt and vendor lock-in. Since MPIs are often ABI-incompatible,
trampolines such as the open-source Wi4MPI library is used when such
cases arise.


### Getting started

### Contributing 

### License

Productivity frameworks for HPC is distributed under the terms of the
MIT license. All new contributions must be made under this license. 

See [LICENSE](LICENSE) and [NOTICE](NOTICE) for details.

SPDX-License-Identifier: MIT.

LLNL-CODE-846462.
