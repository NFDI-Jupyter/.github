<p align="center">
  <img src="Jupyter4NFDI-top.png" alt="Jupyter4NFDI" width="450">
</p>


This GitHub organisation hosts repositories related to [Jupyter4NFDI](https://nfdi-jupyter.de/), a central JupyterHub instance accessible to everyone within the [NFDI- Nationale Forschungsdateninfrastruktur](https://www.nfdi.de). Jupyter4NFDI is one of the [Base4NFDI](https://base4nfdi.de/) services.

Jupyter4NFDI provides browser-based access to computational resources through Jupyter. It supports standard JupyterLab environments, custom Docker images and reproducible environments built from repositories using repo2docker.

You can access Jupyter4NFDI at [hub.nfdi-jupyter.de](https://hub.nfdi-jupyter.de/).

## Funding

Jupyter4NFDI is developed within [Base4NFDI](https://base4nfdi.de/) as part of the German National Research Data Infrastructure (NFDI).

**Funded by the German Research Foundation (DFG) as part of NFDI; grant number 521453681.**

We provide a collection of self-study materials organised into modules, each focusing on a specific task or feature of Jupyter4NFDI. The modules offer practical, step-by-step guidance to help users develop the skills needed to work with the platform, from configuring research environments to managing data and automating workflows.

The materials are designed for independent learning but can also be adapted for use in instructor-led training sessions.


| Module | Description | Repository |
|---|---|---|
| **[Working with different programming languages and kernels](https://nfdi-jupyter.github.io/learn-jupyter4nfdi-languages-kernels/)** | Learn how to use different programming languages and manage kernels in Jupyter4NFDI. | [GitHub](https://github.com/NFDI-Jupyter/learn-jupyter4nfdi-languages-kernels) |
| **[Prepare your project to be Jupyter4NFDI-ready](https://nfdi-jupyter.github.io/learn-jupyter4nfdi-ready/)** | Learn how to configure a GitHub repository so that it can be launched as a reproducible computational environment in Jupyter4NFDI using repo2docker. | [GitHub](https://github.com/NFDI-Jupyter/learn-jupyter4nfdi-ready) |
| **[Automated Notebook Validation](https://nfdi-jupyter.github.io/learn-jupyter4nfdi-automated-validation/)** | Learn how to use GitHub Actions to automatically execute and validate Jupyter notebooks, helping ensure that notebooks remain functional and reproducible. | [GitHub](https://github.com/NFDI-Jupyter/learn-jupyter4nfdi-automated-validation) |
| **[Working with external data storage](https://nfdi-jupyter.github.io/learn-jupyter4nfdi-mouting-data/)** | Learn how to mount external data sources and access data stored outside Jupyter4NFDI from your computational environment. | [GitHub](https://github.com/NFDI-Jupyter/learn-jupyter4nfdi-mouting-data) |
| **[Getting access to GPUs on Jupyter4NFDI](https://nfdi-jupyter.github.io/learn-jupyter4nfdi-gpu/)** | Learn how to request and access GPU resources in Jupyter4NFDI, explore GPU computing capabilities and understand when GPU acceleration can benefit your research workflows. | [GitHub](https://github.com/NFDI-Jupyter/learn-jupyter4nfdi-gpu) |



**Additional training resources**

- **[Jupyter4NFDI-ready repository template](https://github.com/NFDI-Jupyter/jupyter4nfdi-ready-template)**  
  A hands-on exercise repository accompanying the *Prepare your project to be Jupyter4NFDI-ready* module. Use it to practise configuring a repository for launching in Jupyter4NFDI with repo2docker.

- **[Training materials template](https://github.com/NFDI-Jupyter/training-materials-template)**  
  Our training modules are developed using this shared template, providing a consistent structure and presentation across the materials. You are welcome to reuse and adapt the template when developing training materials for your own research community, project or use case.

- **[Jupyter4NFDI workshop slides](https://github.com/NFDI-Jupyter/jupyter4nfdi-slides)**  
  Presentation materials for introducing Jupyter4NFDI and delivering instructor-led workshops. These slides can be used alongside the self-study modules to support interactive training sessions and hands-on exercises. Instructors are welcome to adapt them to suit their audience and workshop format.


### Examples

* **[open-science-jupyter4NFDI](https://github.com/NFDI-Jupyter/open-science-jupyter4NFDI)**
  Example training material for running an Open Science tutorial on the Jupyter4NFDI infrastructure.
* **[prisonners-dillema-jupyter4nfdi](https://github.com/NFDI-Jupyter/prisonners-dillema-jupyter4nfdi)**
  Example Binder-ready training material introducing computer simulation with the Prisoner's Dilemma.

## Repositories

### Jupyter4NFDI infrastructure and services

* **[services](https://github.com/NFDI-Jupyter/services)**
  Documentation and information about Jupyter services within NFDI. The repository also hosts Jupyter4NFDI discussions, support and resource integration processes.

* **[ghactions](https://github.com/NFDI-Jupyter/ghactions)**
  GitHub Actions for integrating repositories with Jupyter4NFDI, including automated execution and testing of notebooks.

## Resources

For documentation and further information, see [nfdi-jupyter.de](https://nfdi-jupyter.de/).
