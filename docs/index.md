# EMOD model documentation

EMOD (Epidemiological MODeling software) is a stochastic, agent-based modeling framework that simulates the simultaneous interactions of agents in an effort to recreate the complex phenomena of disease transmission. Built in C++, the models are feature-rich and designed to track the movement, development, health, and other traits of interest for individuals over a course of lifetimes.

!!! warning "EMOD is no longer under active development"

    EMOD is no longer under active development, so there will be no new feature releases, bug fixes, or model updates. Support is limited to what current users may provide in the GitHub Discussions forum. Model code will remain publicly available, but you are advised to use EMOD at your own risk.

## Available EMOD models and packages

(update text to include a "roadmap" to orient users to the appropriate link below).
The following models and packages are currently available:


<div class="grid cards" markdown>

-   :octicons-graph-16:{ .lg .middle } __EMOD__

    ---

    The source files for building EMOD.

    [:octicons-arrow-right-24: EMOD](https://github.com/EMOD-Hub/EMOD)

-   :material-virus-outline:{ .lg .middle } __EMOD-Generic__

    ---

    Modeling framework best suited for low-complexity disease transmisison, such as measles.

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

    The malaria-specific Python code used to configure and run malaria-based EMOD. It includes vector transmission, within-host parasite dynamics, and malaria-specific interventions.

    [:octicons-arrow-right-24: emodpy-malaria](https://emod-hub.github.io/emodpy-malaria/)

-   :material-water:{ .lg .middle } __emodpy-hiv__

    ---

    The HIV-specific Python code used to configure and run HIV-based EMOD. It includes within-host viral dynamics, HIV virology parameters, and HIV-specific interventions.

    [:octicons-arrow-right-24: emodpy-hiv](https://emod-hub.github.io/emodpy-hiv/)

</div>

<!-- need to update the URLs to EMOD, EMOD-generic, idmtools, etc as we want to link to the docs that are hosted on GHP, not necessarily to repos and definitely not to the RTD docs -->

## idmtools

idmtools is a collection of Python scripts and utilities created to streamline user interactions with disease models. This framework provides the user with tools necessary to complete projects, starting from the creation of input files (if required), to calibration of the model to data, to commissioning and running simulations, through the analysis of results. Modelers can use idmtools to run models locally or send suites of simulations to an HPC or other computing source. This framework is free, open-source, and model agnostic: it can be used to interact with a variety of models, such as custom models written in R or Python, or IDM’s own EMOD.

<div class="grid cards" markdown>

-   :material-language-python:{ .lg .middle } __idmtools__

    ---

    Framework of Python scripts and utilities to streamline modeling workflows.

    [:octicons-arrow-right-24: idmtools](https://docs.idmod.org/projects/idmtools/en/latest/)

-   :material-language-python:{ .lg .middle } __idmtools_local__

    ---

    The local runner enabling the execution of tasks in a local docker container.

    [:octicons-arrow-right-24: idmtools_local](https://docs.idmod.org/projects/idmtools-local/en/latest/)

-   :material-language-python:{ .lg .middle } __idmtools_calibra__

    ---

    Python scripts and utlities to aid in  model calibration.

    [:octicons-arrow-right-24: idmtools_calibra](https://docs.idmod.org/projects/idmtools_calibra/en/latest/)

</div>