---
title: National Scale Interactive Computing
date: 2018-08-22T19:32:16.225Z
draft: false
featured: false
authors:
  - admin
tags:
  - Jupyter
  - Syzygy
  - PIMS
  - 2i2c
categories:
  - research-tech
  - edtech
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---

(Invited post on Jupyter blog: [https://blog.jupyter.org/national-scale-interactive-computing-2c104455e062](https://blog.jupyter.org/national-scale-interactive-computing-2c104455e062))

This is an invited post from Jim Colliander, Professor of Mathematics at UBC and Director of the [Pacific Institute for the Mathematical Sciences](http://www.pims.math.ca/).¹

In 2017, the [Pacific Institute for the Mathematical Sciences (PIMS)](http://www.pims.math.ca/), in partnership with [Compute Canada](https://www.computecanada.ca/featured/compute-canada-and-pims-launch-jupyter-service-for-researchers/) and [Cybera](https://www.cybera.ca/services/jupyter-all-in-one-science-platform/), launched [Syzygy](https://syzygy.ca/), a cloud-hosted interactive computing platform that delivers [JupyterHub deployments](https://jupyter.org/) for [universities across Canada](https://www.google.com/maps/d/embed?mid=1nzSAGLSn8eWdfQ6K7zTw-31h82I&hl=en).

Syzygy has been used by over 16,000 students at 20 universities. The main results of the Syzygy experiment so far are:

1. Demand for interactive computing is ubiquitous² and growing strongly at universities.
2. The Jupyter ecosystem is an effective way to deliver interactive computing.
3. A scalable, sustainable, and cost-effective interactive computing service for universities is needed as soon as possible.

## Demand for interactive computing

Both research and teaching at universities are adapting to major societal changes driven by explosions in data and computational tools. New educational programs that prepare students to think computationally are emerging, while research strategies are changing in ways that are more open, reproducible, collaborative, and interdisciplinary. These transformations are inextricably linked and are accelerating demand for interactive computing. The Syzygy experiment has shown that using Jupyter in educational programs drives interest in using Jupyter for research (and vice versa). For example, students in mathematics, statistics, and computer science [collaborated with a researcher from St. Paul’s Hospital in Vancouver using Syzygy](https://medium.com/pims-math/saving-lives-with-data-and-math-b697667d1cd7) to identify new pathways to prevent death from sepsis. Research communities typically need access to deeper computational resources and often span multiple universities, but the common thread is the need to expand access to interactive computing.

![syzygy map](https://miro.medium.com/max/956/1*L8MzmheO2NZQBH0t-BGpFg.png)

A map of JupyterHub deployments deployed by Syzygy.

## Technical milestone achieved

The Syzygy project has demonstrated that it’s possible to deploy tools for interactive computation at a national scale rapidly and efficiently using an entirely open source technology stack. Students, faculty and staff across Canada use Syzygy to access Jupyter through their browsers with their university single-sign-on credentials. The JupyterHubs range from a “standard” configuration to bespoke environments with specially curated tools and data integrations. This richness is possible because of the architecture of the Syzygy and Jupyter projects and the flexibility of the underlying cloud resources. As a case-study, Syzygy demonstrates that the Jupyter community has achieved a significant technical milestone: interactive computing can be delivered at national scale using cloud technologies.

## Service level requirements

The validation that interactive computing can be technically delivered at national scale prompts universities to ask a variety of questions. Can interactive computing service be delivered robustly? How will users be supported? What are the uptime expectations? What is the data security policy? How is privacy protected? Can the robustness of the service be clarified in a service level agreement? Syzygy, as an experimental service offered to universities at no charge and without a service level agreement, does not properly address these questions. To advance on their education-research-service mission and address growing demand, universities need a reliable interactive computing service with a service level agreement.

## What’s next?

How should universities address their needs for interactive computing over the next five years? Right now, universities are following two primary approaches:

+ 🙏 Ad hoc: faculty figure out how to meet their own needs for interactive computing; IT staff deploys JupyterHub on local or commercial cloud servers; this approach gives universities control over their deployments and hardware, though requires time and expertise that many may not have.
+ 🎩 Use a cloud provider’s service: Google Colab, Amazon Sagemaker, Microsoft Azure Notebooks, IBM Watson Studio; this approach allows universities to quickly launch interactive computing services, with a loss of flexibility and some risks by becoming reliant upon a particular vendor’s closed-source and proprietary software.

These approaches are not sustainable over the long term. If universities all deploy their own JupyterHub services, many will need technical expertise they do not currently have and will involve a significant duplication of effort. If universities rely on hosted cloud notebook services, the reliance on proprietary technology will impair their ability to switch between different cloud vendors, change hardware, customize software, etc. Vendor lock-in will limit the ability of universities to respond to changes in price for the service. Universities will lose agility in responding to changes in faculty, staff, and student computing needs.

There is a third option that addresses the issues with these two approaches and generates other benefits for universities:

+ 🤔 Form an interactive computing consortium: universities collaborate to build an interactive computing service provider aligned with their missions to better serve their students, facilitate research, and avoid risks associated with vendor lock-in.

To retain control over their interactive computing stacks, avoid dependence⁴ on cloud providers, and accelerate the emergence of new programs, universities should work together to deploy interactive computing environments in a vendor-agnostic manner. This might take the form of a consortium — an organization dedicated to serving the needs of universities through customized shared infrastructure for interactive computing. The consortium would also ensure that universities will continue to play a leadership role in the development of the interactive computing tools used for education and research.

The Syzygy experiment confirmed that growing demand for interactive computation within universities can be supplied with the available technologies advanced by the Jupyter open source community. In the coming year, we aim to build upon the success of the Syzygy experiment and seed an initial node of a consortium in Canada with the intention of fostering a global network of people invested in advanced interactive computing. If you are interesting in partnering, [please get in touch!](https://ten.blue/2i2c/#/3/4) See [this Jupyter Community Forum post](https://discourse.jupyter.org/t/creating-national-infrastructure-for-jupyter-environments/1966) to continue the discussion.

    The author gratefully acknowledges feedback on this piece from Ian Allison, Lindsey Heagy, Chris Holdgraf, Fernando Perez, and Lindsay Sill.
    Interactive computing needs have been identified in agriculture, applied mathematics, astronomy, chemistry, climate science, computer science, data science, digital humanities, ecology, economics, engineering, genomics, geoscience, health sciences, K-12 education, neuroscience, political science, physics, pure mathematics, statistics, and sociology.
    Relying on commercial cloud vendors to provide the interactive computing service for universities risks recreating the problems associated with scientific publishing that emerged with the internet.
