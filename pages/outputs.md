---
title: Outputs
description:
background: /assets/img/chuttersnap-146799-unsplash.jpg
permalink: /outputs/
---

The research outputs from PAStor will be disseminated through top scientific venues in the HPC and storage fields and released as an open-source prototype. The prototype will provide the first building block towards a novel storage architecture suited for exascale computing infrastructures. The project will include both senior researchers and students who are working on PhD and MSc thesis focused on the scope of the project.

This page will be updated during the project duration.

---
#### Publications

* Dantas M, Leitão D, Cui P, Macedo R, Liu X, Xu W, Paulo J. Accelerating Deep Learning Training Through Transparent Storage Tiering. IEEE/ACM International Symposium on Cluster, Cloud and Internet Computing (CCGrid). 2022

* Macedo R, Tanimura Y, Haga J, Chidambaram V, Pereira J, Paulo J. PAIO: General, Portable I/O Optimizations With Minor Application Modifications. USENIX Conference on File and Storage Technologies (FAST). 2022

* Macedo R, Correia C, Dantas M, Brito C, Xu W, Tanimura Y, Haga J, Paulo J. The Case for Storage Optimization Decoupling in Deep Learning Frameworks. Workshop on Re-envisioning Extreme-Scale I/O for Emerging Hybrid HPC Workloads (REX-IO), colocated with IEEE Cluster. 2021

* Dantas M, Leitão D, Correia C, Macedo R, Xu W, Paulo J. Monarch: Hierarchical Storage Management for Deep Learning Frameworks. . Workshop on Re-envisioning Extreme-Scale I/O for Emerging Hybrid HPC Workloads (REX-IO), colocated with IEEE Cluster. 2021

* Miranda M, Esteves T, Portela B, Paulo J. S2Dedup: SGX-enabled Secure Deduplication. ACM International Systems and Storage Conference (SYSTOR). 2021

* Macedo R, Tanimura Y, Haga J, Chidambaram V, Pereira J., Paulo J. PAIO: A Software-Defined Storage Data Plane Framework. ArXiv – Computing Research Repository (CoRR), 2021. 


----
#### Thesis

* Ricardo Macedo, PhD Thesis - User-level Software-Defined Storage Data Planes (on-going).
* Mariana Miranda, PhD Thesis - Distributed and Dependable SDS Control Plane for HPC (on-going).
* Marco Dantas, MSc Thesis - Accelerating Deep Learning Training through Transparent Storage Tiering (on-going).
* Cláudia Correia, MSc Thesis - PRISMA: A Prefetching Storage Middleware for Accelerating Deep Learning Frameworks, 2021.

----
#### Talks and Events

* October 21, 2021 - Virtual e-poster of PAStor. Presented at the UT AUstin Portugal 2021 Annual Conference. Available [here](https://youtu.be/ojO2HViFVQc). 

* September 20, 2021 - The PAStor project was one of the supporters for the 1st Workshop on High-Performance and Reliable Big Data (HPBD’21), co-located with SRDS 2021. The workshop included researchers from the project in the organization and technical committees. The workshop’s website is available [here](https://hpbd-21.github.io).

* September 16, 2021 - Presentation of PAStor outputs at the Webinar Series *On the Road to HPC: Major Challenges and New Opportunities*. Title of the talk: *Is HPC ready for “Big” Data Storage?*. Video recording available [here](https://www.youtube.com/watch?v=IqDrwYyB8Oc&t=2s).

* June 23, 2021 - PAStor's presentation at UT Austin Portugal Program's workshop "Better prepared: Strengthening societies through international scientific collaboration". Collocated with Encontro Ciência'21 in Lisbon, Portugal. Video recording available [here](https://youtu.be/DlRbBe1K0W8).

---
#### Prototypes

* [PAIO](https://github.com/dsrhaslab/paio) a general-purpose SDS framework that enables system designers to build custom-made data plane stages. PAIO eases the implementation of complex storage mechanisms (e.g., I/O schedulers, caches, and token-buckets) that can adapt to different I/O workflows and policies.
A data plane stage built with PAIO allows the classification and differentiation of I/O requests, and the enforcement of different mechanisms according to user-defined storage policies.

* [Monarch](https://github.com/dsrhaslab/monarch) a storage data plane for hierarchical storage management. This solution leverages the existing storage tiers present at modern supercomputers (e.g., compute node’s local storage, PFS) to improve DL training performance and alleviate the current I/O pressure of the shared PFS.

* [Prisma](https://github.com/dsrhaslab/prisma) a storage data plane that accelerates the training performance of DL frameworks. It implements a parallel data prefetching mechanism that reads training data in advance and stores it in an in-memory buffer to serve incoming I/O requests of DL frameworks.

* [S2Dedup](https://github.com/mmm97/S2Dedup) leverages intel SGX to enable privacy-preserving deduplication at untrusted servers. The open-source prototype, built with SPDK, supports multiple secure schemes. Deduplication is more and more used to optimize the performance and reduce the storage costs of Big Data applications (e.g., Deep Learning frameworks) that deal with large quantities of information. Our solution enables this technique at third-party infrastructures, such as HPC centers, without compromising the privacy of users’ sensitive data.

---
