# Best Practices for CernVM-FS in HPC

<p align="center">
<img src="img/cvmfs_hpc.png" alt="CernVM-FS logo" width="40%"/></br>
</p>


This is an introductory tutorial to [CernVM-FS](https://cernvm.cern.ch/fs/), the CernVM File System,
with a focus on employing it in the context of High-Performance Computing (HPC).

In this tutorial you will learn what CernVM-FS is, how to get access to existing CernVM-FS repositories,
how to configure CernVM-FS, and how to use CernVM-FS [repositories](appendix/terminology.md#repository)
on HPC infrastructure.

<div markdown="1" style="text-align:center;">
**[Ready to go? Click here to start the tutorial!](cvmfs/what-is-cvmfs.md)**
</div>


## Recording

A first virtual edition of this tutorial was held on 4 December 2023,
the recording is available here:

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/L0Mmy7NBXDU?si=Ob0DtYN2FH3K169V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<br/><a href="https://raw.githubusercontent.com/multixscale/cvmfs-tutorial-hpc-best-practices/main/files/Best-Practices-for-CernVM-FS-in-HPC-20231204.pdf">
<em>slides (PDF) available for download here</em></a>
</p>

### Slides

[Available for download here](https://raw.githubusercontent.com/multixscale/cvmfs-tutorial-hpc-best-practices/main/files/Best-Practices-for-CernVM-FS-in-HPC-20231204.pdf)

## Intended audience

This tutorial is intended for people with a background in HPC (system administrators, support team members,
end users, etc.) and who are new to CernVM-FS; no specific prior knowledge or experience with it is required.

We expect it to be most valuable to people who are interested in using or providing access to one or more existing
CernVM-FS repositories on HPC infrastructure.


## Prerequisites

- Basic knowledge of Linux shell environment
- Basic knowledge of networking (IP address, port, latency)
- Basic knowledge of Linux file systems
- Familiarity with High-Performance Computing environments is a plus
- Hands-on experience with running scientific software workloads is a plus


## Practical information

### Registration

Attendance is free, but **registration is required**: <https://event.ugent.be/registration/cvmfshpc202312>.

Registration for online tutorial on Mon 4 Dec 2023 is **closed** *(since Sun 3 Dec 2023)*

### Slack channel

Dedicated channel in EESSI Slack: [`#cvmfs-best-practices-hpc`](https://eessi-hpc.slack.com/archives/C068DV7GY3V)

[Click here to join the EESSI Slack](https://join.slack.com/t/eessi-hpc/shared_invite/zt-1wqy0t8g6-PZJTg3Hjjm5Fm3XEOkzECg)

## MultiXscale

<div align="center">
<a href="https://www.multixscale.eu">
<img src="img/logos/multixscale_logo.png" alt="MultiXscale logo" width="50%"/>
</a>
</div>

This tutorial was developed and organised in the context of the [MultiXscale EuroHPC
Centre-of-Excellence](https://www.multixscale.eu).

Funded by the European Union. This work has received funding from the [European High Performance Computing Joint
Undertaking (JU)](https://eurohpc-ju.europa.eu) and countries participating in the project under grant agreement No 101093169.

## Contributors

* Jakob Blomer (CERN, Switzerland)
* Bob Dröge (University of Groningen, The Netherlands)
* Kenneth Hoste (Ghent University, Belgium)
* Alan O'Cais (University of Barcelona, Spain; CECAM)
* Lara Peeters (Ghent University, Belgium)
* Laura Promberger (CERN, Switzerland)
* Thomas Röblitz (University of Bergen, Norway)
* Caspar van Leeuwen (SURF, The Netherlands)
* Valentin Völkl (CERN, Switzerland)


## Additional resources

* [CernVM-FS website](https://cernvm.cern.ch/fs)
* [CernVM-FS documentation](https://cvmfs.readthedocs.io)
* [CernVM-FS @ GitHub](https://github.com/cvmfs)
* [CernVM-FS forum](https://cernvm-forum.cern.ch)
* [Introduction to CernVM-FS by *Jakob Blomer (CERN)* (2021)](https://easybuild.io/eum21/#cvmfs-talk)
* [Introductory tutorial on CernVM-FS (2021)](https://cvmfs-contrib.github.io/cvmfs-tutorial-2021)
