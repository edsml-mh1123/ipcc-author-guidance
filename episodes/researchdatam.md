---
title: "Research Data and Software Managment"
teaching: 10
exercises: 1
---

:::::::::::::::::::::::::::::::::::::: questions

- What is research data?
- What is research software?
- Why is important to properly describe, protect and share research data and software?
  
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Understand the importance of disseminating research data and the code used for its generation
- Undertand the benefits of a Research Data Management plan (via the Turing Way)
- Understad the difference between research code and software and the benefits of a Software Management Plan

::::::::::::::::::::::::::::::::::::::::::::::::


## Research Data Management

Climate science has significant public interest, as it affects people’s lives, economies, and ecosystems. Effective Research Data Management supports open science initiatives by making data accessible to the public, policymakers, and other stakeholders, increasing transparency, and encouraging public engagement. This openness builds trust and fosters greater awareness and informed decision-making regarding climate action.

Research Data Management underpins the accuracy, reproducibility, and impact of research findings. It supports collaborative and transparent science. In IPCC it helps ensure that investments in the realisation of the assessments continue to benefit scientific inquiry and public policy.

::::::::::::::::::::::::::::::::::::: callout

"The Turing Way", an open science and community-driven project focused on making data science more accessible, understandable, and effective, offers a general overview on the purposes and practices that motivates RDM, illustrating guidelines and useful approaches to put that into practice. 

[Reproducible Research according to the Turing Way](https://book.the-turing-way.org/reproducible-research/rdm) 

For instance some IPCC Working Groups may propose a [Data Management Plan](https://book.the-turing-way.org/reproducible-research/rdm/rdm-dmp).


::::::::::::::::::::::::::::::::::::::::::::::::

## Software Management Plans

Before diving into Software Management Plans, it is important to highlight the distinctions between research code and research software

**Rresearch Code** is the individual, often experimental, coding work that solves specific problems in the research process, It is often a custom solution developed for a specific research question or experiment. For instance the script used to generate one of the figures in the IPCC reports. 

**Research Software** is a broader, often more stable tool or platform that assists in conducting research across various stages of the workflow. Both are critical components of modern research, with research code often contributing to the development of research software. Eg. the [ESMVal Tool](https://esmvaltool.org/)

Key characteristics of **Research Code**

- Custom and Domain-Specific: It is typically tailored to address the unique needs of a particular research task or domain (e.g., bioinformatics, physics simulations, social sciences).
- Prototyping and Experimentation: Often experimental, evolving during the research process as the researcher tests and refines ideas. This could be in the form of scripts for data collection, analysis, or visualization.
- Reproducible: In many cases, research code is shared openly to promote reproducibility and transparency. Open-source platforms like GitHub, GitLab, and Bitbucket are commonly used for sharing and collaborating on research code. Scripts my be expresssed as Jupyter Notebooks and re-executed in Jupyter platforms like Jupyter Lab, Jupyter Hub or Binder.

Key characteristics of **Research Sofware**

- Comprehensive and integrated: supporting tasks like data management, analysis, and visualization, often with a user-friendly interface. For instance, tools like SPSS, MS Excel, or Tableau.
- Production-ready: stable, and maintainable, featuring error handling and documentation. It can be domain-specific (e.g., statistical tools, simulation platforms) or general-purpose (e.g., text editors, database systems) and is widely used in research.

::::::::::::::::::::::::::::::::::::: callout
Some working groups may consdier to propose a Software Management Plan. This is usually a document that addresses questions such as.

- What does it do?
- Who is it for?
- What resources does it need?
- Who is responsible?
- What licence does it needs?

Having such clarity early on, avoid problems later, with the objective of facilitatng IPCC to deliver [FAIR code and software](https://www.rug.nl/digital-competence-centre/research-data/research-software-management/fair-research-software?lang=en). Example of SMPs exists in many organisations. A detailed list of elements that are relevant in the defintion of [SMP for Research Code and Software](https://esciencecenter-digital-skills.github.io/research-software-support/modules/softwaremanagementplans/slides-smp) is provided by the Dutch insitute for eScience.

In IPCC, SMPs can have the scope to define key aspects which should be taken into account by the authors, depending whether they will develop and release simple scripts, for data analysis and visualisation purposes, or more complex Research Software, like for instance a new [IPCC Atlas](https://interactive-atlas.ipcc.ch/).

::::::::::::::::::::::::::::::::::::::::::::::::

## Challenge 1: Can you classify the following software types?
::::::::::::::::::::::::::::::::::::: challenge



1. 
2. 
:::::::::::::::::::::::: solution

## Output

1. 

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints

- 
- 

::::::::::::::::::::::::::::::::::::::::::::::::
