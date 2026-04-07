# EMOD model documentation

EMOD (Epidemiological MODeling software) is a stochastic, agent-based modeling framework that simulates the simultaneous interactions of agents in an effort to recreate the complex phenomena of disease transmission. Built in C++, the models are feature-rich and designed to track the movement, development, health, and other traits of interest for individuals over a course of lifetimes.

!!! warning "EMOD is no longer under active development"

    EMOD will not receive new features, bug fixes, or model updates. Community support is available through the GitHub Discussions forum, and model code will remain publicly accessible. We recommend evaluating whether EMOD is the right fit before starting new work.

## Available models and utilities

We provide both modeling software and workflow tools to support an end-to-end simulation pipeline. EMOD is the disease model framework, offering disease-specific models for malaria and HIV alongside Python packages for configuring and running simulations. idmtools is a model-agnostic framework that handles the surrounding infrastructure: job commissioning, HPC integration, calibration, and more. While each can be used independently, we recommend using them together for a seamless, integrated workflow.

### EMOD

The EMOD framework is powerful and flexible, and can be customized to examine a variety of epidemiological problems. Source code is available for those interested in modifying code to create custom models, and various transmission modes are available to investigate specific disease-oriented questions.


<div class="grid cards" markdown>

-   :octicons-graph-16:{ .lg .middle } __EMOD__

    ---

    The source files for building EMOD.

    [:octicons-arrow-right-24: EMOD](https://github.com/EMOD-Hub/EMOD)

-   :material-virus-outline:{ .lg .middle } __EMOD-Generic__

    ---

    Modeling framework best suited for low-complexity disease transmission, such as measles.

    [:octicons-arrow-right-24: EMOD-Generic](https://github.com/EMOD-Hub/EMOD-Generic)

-   :material-api:{ .lg .middle } __emod-api__

    ---

    The Python API used for editing EMOD files.

    [:octicons-arrow-right-24: emod-api](https://emod-hub.github.io/emod-api/)

-   :material-language-python:{ .lg .middle } __emodpy__

    ---

    The Python code used to configure and run EMOD simulations.

    [:octicons-arrow-right-24: emodpy](https://emod-hub.github.io/emodpy/)

-   :fontawesome-solid-mosquito:{ .lg .middle } __emodpy-malaria__

    ---

    The malaria-specific model and Python code used to configure and run malaria-based EMOD. It includes vector transmission, within-host parasite dynamics, and malaria-specific interventions.

    [:octicons-arrow-right-24: emodpy-malaria](https://emod-hub.github.io/emodpy-malaria/)

-   :material-water:{ .lg .middle } __emodpy-hiv__

    ---

    The HIV-specific model and Python code used to configure and run HIV-based EMOD. It includes within-host viral dynamics, HIV virology parameters, and HIV-specific interventions.

    [:octicons-arrow-right-24: emodpy-hiv](https://emod-hub.github.io/emodpy-hiv/)

</div>

<!-- need to update the URLs to EMOD, EMOD-generic, idmtools, etc as we want to link to the docs that are hosted on GHP, not necessarily to repos and definitely not to the RTD docs -->

### idmtools

idmtools is a collection of Python scripts and utilities that streamlines the full modeling workflow: input file creation, model calibration, commissioning simulations (both locally and on an HPC), and analyzing results. While idmtools is model-agnostic and compatible with custom R or Python models, it is purpose-built to work seamlessly with EMOD.

<div class="grid cards" markdown>

-   :material-language-python:{ .lg .middle } __idmtools__

    ---

    Framework of Python scripts and utilities to streamline modeling workflows.

    [:octicons-arrow-right-24: idmtools](https://institutefordiseasemodeling.github.io/idmtools/)

-   :material-language-python:{ .lg .middle } __idmtools_local__

    ---

    The local runner enabling the execution of tasks in a local docker container.

    [:octicons-arrow-right-24: idmtools_local](https://docs.idmod.org/projects/idmtools-local/en/latest/)

-   :material-language-python:{ .lg .middle } __idmtools_calibra__

    ---

    Python scripts and utilities to aid in model calibration.

    [:octicons-arrow-right-24: idmtools_calibra](https://institutefordiseasemodeling.github.io/idmtools-calibra/)

</div>
