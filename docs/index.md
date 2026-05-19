---
title: Home
---

# EMOD model documentation

EMOD (Epidemiological MODeling software) is a stochastic, agent-based modeling
framework that simulates the simultaneous interactions of agents in an effort
to recreate the complex phenomena of disease transmission. Built in C++, the
models are feature-rich and designed to track the movement, development,
health, and other traits of interest for individuals over a course of lifetimes.

## Project status

EMOD-Hub projects are provided as open source software under the MIT License for
community use, research, and development.

**Unless otherwise noted, these projects are no longer actively maintained or supported
by IDM or the Gates Foundation.**

Community contributions are welcome, and trusted collaborators may review and
merge pull requests, but no guarantees are made regarding support, pull request
review, security response, maintenance, or release timelines.

## Getting started

<div class="grid cards" markdown>

-   :material-school:{ .lg .middle } __emodpy-hiv__

    ---

    Tutorials for emodpy-hiv.

    [:octicons-arrow-right-24: emodpy-hiv][emodpy-hiv_tutorial]

-   :material-school:{ .lg .middle } __emodpy-malaria__

    ---

    Tutorials for emodpy-malaria.

    [:octicons-arrow-right-24: emodpy-malaria][emodpy-malaria_tutorial]

-   :material-school:{ .lg .middle } __emodpy-workflow__

    ---

    Workflow examples with emodpy-hiv.

    [:octicons-arrow-right-24: emodpy-workflow][emodpy-workflow]

-   :material-school:{ .lg .middle } __EMOD-Generic-Scripts__

    ---

    Example models for the Generic branch of EMOD.

    [:octicons-arrow-right-24: EMOD-Generic-Scripts][emod-generic-scripts]

</div>


## Available models and utilities

EMOD is the disease model framework, offering disease-specific models for malaria and HIV alongside Python packages for configuring and running simulations. The idmtools package is a model-agnostic framework that handles the surrounding infrastructure: job commissioning, HPC integration, calibration, and more. While each can be used independently, we recommend using them together for a seamless, integrated workflow.

### EMOD

The EMOD framework is powerful and flexible, and can be customized to examine a variety of epidemiological problems. Source code is available for those interested in modifying code to create custom models, and various transmission modes are available to investigate specific disease-oriented questions.

<div class="grid cards" markdown>

-   :material-virus:{ .lg .middle } __EMOD__

    ---

    The source files for building EMOD.

    [:octicons-arrow-right-24: EMOD][emod]

-   :material-virus-outline:{ .lg .middle } __EMOD-Generic__

    ---

    Modeling framework best suited for low-complexity disease transmission, such as measles.

    [:octicons-arrow-right-24: EMOD-Generic][emod-generic]

-   :material-api:{ .lg .middle } __emod-api__

    ---

    The Python API used for editing EMOD files.

    [:octicons-arrow-right-24: emod-api][emod-api]

-   :material-language-python:{ .lg .middle } __emodpy__

    ---

    Shared Python workflow infrastructure used to configure and run EMOD simulations.

    [:octicons-arrow-right-24: emodpy][emodpy]

-   :fontawesome-solid-mosquito:{ .lg .middle } __emodpy-malaria__

    ---

    The malaria-specific model and Python code used to configure and run malaria-based EMOD. It includes vector transmission, within-host parasite dynamics, and malaria-specific interventions.

    [:octicons-arrow-right-24: emodpy-malaria][emodpy-malaria]

-   :material-water:{ .lg .middle } __emodpy-hiv__

    ---

    The HIV-specific model and Python code used to configure and run HIV-based EMOD. It includes within-host viral dynamics, HIV virology parameters, and HIV-specific interventions.

    [:octicons-arrow-right-24: emodpy-hiv][emodpy-hiv]

</div>

### idmtools

The idmtools package is a collection of Python scripts and utilities that streamlines the full modeling workflow: input file creation, model calibration, commissioning simulations (both locally and on an HPC), and analyzing results. While idmtools is model-agnostic and compatible with custom R or Python models, it is purpose-built to work seamlessly with EMOD.

<div class="grid cards" markdown>

-   :material-language-python:{ .lg .middle } __idmtools__

    ---

    Framework of Python scripts and utilities to streamline modeling workflows.

    [:octicons-arrow-right-24: idmtools][idmtools]

-   :material-language-python:{ .lg .middle } __idmtools container__

    ---

    The local runner enabling the execution of tasks in a docker container.

    [:octicons-arrow-right-24: idmtools-local][idmtools_container]

-   :material-language-python:{ .lg .middle } __idmtools calibra__

    ---

    Python scripts and utilities to aid in model calibration.

    [:octicons-arrow-right-24: idmtools-calibra][idmtools_calibra]

</div>
