---
layout: default
---
[Home](index.html) | [Papers](papers.html) | [Presentations](presentations.html) | [Participants](participants.html) | [News](news.html)

# About

The **RAMSES project** was launched in 2014 with the goal of developing a new science of **end-to-end analytical performance modeling** that will transform understanding of the behavior of science workflows in extreme-scale science environments. Much as modern design tools permit digital pre-assembly and simulated flight of new aircraft before they are built, predictive control during flight, and predictive trending for failure detection, our new methods will provide a basis for tools that allow developers and users of science workflows and operators of science facilities to [***explain***, ***predict*** and ***optimize***](files/img/epo.png).

# Motivation

Modern science is increasingly data-intensive, compute-intensive, distributed, and collaborative. The science workflows that underpin a typical project often couple multiple instruments, data stores, computational tools, and people. The performance of these science workflows has a profound impact on both the pace of scientific discovery and the return on investment from DOE’s multi-billion-dollar facilities budget. Yet our ability to predict the behavior of a science workflow before it is implemented, to explain why performance does not meet design goals, and to architect science environments to meet workflow needs are all grossly inadequate. These are the challenges that RAMSES will address.

The foundation for this new science of workflow modeling is the fusion of multiple distinct threads of inquiry that have not, until now, been adequately connected: namely, first-principles performance modeling within individual sub-disciplines (e.g., networks, storage systems, applications), and data-driven methods for evaluating, calibrating, and synthesizing models of complex phenomena. What makes this fusion necessary is the drive to explain, predict, and optimize not just individual system components but complex end-to-end workflows. What makes this fusion possible is the unique multidisciplinary expertise of the RAMSES team and an unprecedented experimental program that will collect data on a broad range of model components and end-to-end application behaviors. The resulting data will be stored in a new performance database, along with estimated parameters and other information on model and workflow performance. Together, these program elements will allow us to evaluate existing and new models, synthesize new models, and assess model composition methods with a breadth and rigor not previously possible.

# Our mission

We intend that RAMSES research will not only advance knowledge but also provide a path to transforming how science workflows and science infrastructures are designed, implemented, and operated across the DOE science complex. To this end, we will prototype a suite of end-to-end analytical performance models, experimental testing tools, and numerical methods. We will also develop a performance advisor that will provide actionable feedback regarding achieved performance. We will apply these tools to a range of performance analysis problems, including prediction, explanation, and optimization of performance metrics for the Globus file transfer service. This work will both showcase what RAMSES technologies can do and allow us to obtain feedback from our stakeholder community.

The potential benefits of RAMSES research for science and technology are considerable. New modeling capabilities that enable better understanding of workflow and infrastructure performance have the potential to accelerate discovery across dozens of DOE science facilities that are used by tens of thousands of researchers from across the nation. To give just two examples: acceleration of a data analysis workflow used at a DOE experimental facility can permit real-time rather than post hoc user feedback, increasing the efficiency of the research performed at that facility by orders of magnitude. Workflow optimizations that reduce the number of CPUs required for analysis allow us to increase the number of people who can profit from leadership computing facilities. Increasingly, workflows comparable to those encountered in extreme-scale
science are appearing in industry as well, providing opportunities for yet broader impact.

# RAMSES-II

In the next phase of RAMSES (RAMSES-2), we propose to build on these successes to focus on specific challenges associated with
next-generation science experiments, in which experimental apparatus, supercomputers, storage systems, and other devices are connected by high-speed networks.
Moving beyond data transfers, we focus on a broad class of streaming scenarios, including coordinated monitoring and steering of  experiments, computations, and storage. They provide the next generation of science enabling capabilities, while challenging the underlying workflow implementations and optimizations.
Using a mix of prototyping, experimentation, and modeling, we aim to produce new understanding of how
individual workflows, collections of workflows,
and science facilities can be engineered to enable efficient and cost-effective workflow execution.
We envision this work involving innovations at multiple levels.
We will prototype new data streaming applications and mechanisms,
building on early work conducted with the Advanced Photon Source, Advanced Light Source, and other facilities,
with the goal of producing a framework in which a wide range of streaming use cases and scenarios can be explored,
to include data ingest into different levels of the storage hierarchy on next-generation supercomputers.
We will extend previous work on experimental characterization, data-driven modeling, and analytical modeling of file transfers to encompass such scenarios.
We will develop testbed and production-level experiments and analytics to characterize and assess the performance of TCP variants and UDP-based transport for sustained streaming, on-demand data push and pull, and control traffic, by building on concave-convex throughput profile characterizations and Poincare dynamics analysis of transport protocols.
At the facility level and beyond,
we will investigate methods for co-optimizing not only individual workflows
but also collections of workflows and the underlying science facility fabric.

RAMSES is supported by the US Department of Energy's [Office of Advanced Scientific Computing Research](http://science.energy.gov/ascr/) (ASCR), under the leadership of Rich Carlson.

# RAMSES PIs
* Ian Foster, Argonne National Laboratory (Principal Investigator)
* Gagan Agarwal, The Ohio State University (Co-Investigator)
* Nagi Rao, Oak Ridge National Laboratory (Co-Investigator)
* Brian Tierney, Lawrence Berkeley National Laboratory (Co-Investigator)
* Don Towsley, University of Massachusetts (Co-Investigator)

# RAMSES-2 PIs
* Ian Foster, Argonne National Laboratory (overall Principal Investigator)
* Nagi Rao, Oak Ridge National Laboratory (Co-PI)
* Raj Kettimuthu, Argonne National Laboratory (Co-PI)
