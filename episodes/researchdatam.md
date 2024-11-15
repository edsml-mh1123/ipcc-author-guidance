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

## Software Management 

Before dwelving into sofware management, it is worth hlighting the differences between Research Code and Research Software. 

**Rresearch Code** is the individual, often experimental, coding work that solves specific problems in the research process, It is often a custom solution developed for a specific research question or experiment. For instance the scripts used to generate one of the figures in the IPCC reports. 

**Research Software** is a broader, often more stable tool or platform that assists in conducting research across various stages of the workflow. Both are critical components of modern research, with research code often contributing to the development of research software. Eg. the ESMVal Tool

::::::::::::::::::::::::::::::::::::: callout

Key characteristics of **Research Code**

- Custom and Domain-Specific: It is typically tailored to address the unique needs of a particular research task or domain (e.g., bioinformatics, physics simulations, social sciences).
- Prototyping and Experimentation: Research code is often experimental, evolving during the research process as the researcher tests and refines ideas. This could be in the form of scripts for data collection, analysis, or visualization.
- Rapid Development: Researchers often write code quickly and iteratively to meet the immediate demands of their experiments. and shared via Open-source platforms like GitHub, GitLab.
- Reproducible: In many cases, research code is shared openly to promote reproducibility and transparency. Open-source platforms like Jupyter Lab, Reproducible: In many cases, research code is shared openly to promote reproducibility and transparency. Open-source platforms like GitHub, GitLab, and Bitbucket are commonly used for sharing and collaborating on research code. Scripts my be expresssed as Jupyter Notebooks and re-executed in Jupyter platforms like Jupyter Lab, Jupyter Hub or Binder.

Key characteristics of **Research Sofware**

- Comprehensive and integrated, supporting tasks like data management, analysis, and visualization, often with a user-friendly interface.
- Production-ready, stable, and maintainable, featuring error handling and documentation. It can be domain-specific (e.g., statistical tools, simulation platforms) or general-purpose (e.g., text editors, database systems) and is widely used in research.
- Collaboration and sharing, such as through platforms like LaTeX or tools like SPSS, MS Excel, or Tableau for data analysis.

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge

## Challenge 1: Can you classify the following data types?

1. A map used in the report
2. Output from a CMIP6 model
3. Model agreement on changes in temperature in a warming scenario

:::::::::::::::::::::::: solution

## Output

1. A map used in the report: Final
2. Output from a CMIP6 model: Input
3. Model agreement on changes in temperature in a warming scenario: Intermediate

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints

- 
- 

::::::::::::::::::::::::::::::::::::::::::::::::
