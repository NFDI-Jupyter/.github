<p align="center">
  <img src="Jupyter4NFDI-top.png" alt="Jupyter4NFDI" width="450">
</p>


This GitHub organisation hosts repositories related to [Jupyter4NFDI](https://nfdi-jupyter.de/), a central JupyterHub instance accessible to everyone within the [NFDI- Nationale Forschungsdateninfrastruktur](https://www.nfdi.de). Jupyter4NFDI is one of the [Base4NFDI](https://base4nfdi.de/) services.

Jupyter4NFDI provides browser-based access to computational resources through Jupyter. It supports standard JupyterLab environments, custom Docker images and reproducible environments built from repositories using repo2docker.

You can access Jupyter4NFDI at [hub.nfdi-jupyter.de](https://hub.nfdi-jupyter.de/).

## Funding

Jupyter4NFDI is developed within [Base4NFDI](https://base4nfdi.de/) as part of the German National Research Data Infrastructure (NFDI).

**Funded by the German Research Foundation (DFG) as part of NFDI; grant number 521453681.**

## Training resources

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


## Examples

* **[open-science-jupyter4NFDI](https://github.com/NFDI-Jupyter/open-science-jupyter4NFDI)**
  Example training material for running an Open Science tutorial on the Jupyter4NFDI infrastructure.
* **[prisonners-dillema-jupyter4nfdi](https://github.com/NFDI-Jupyter/prisonners-dillema-jupyter4nfdi)**
  Example training material introducing computer simulation with the Prisoner's Dilemma.

#### Examples of Jupyter4NFDI use across research domains

The [Jupyter4NFDI Incubators](https://github.com/NFDI-Jupyter/services/discussions) demonstrate how researchers from different disciplines can use Jupyter4NFDI to develop, share and execute computational research workflows.

| Domain | Example | Description | Links |
|---|---|---|---|
| High-performance computing / Data analytics | **HEAT** | Interactive tutorials demonstrating parallel and distributed data analytics using the Heat Python library. | [Run on Jupyter4NFDI](https://hub.nfdi-jupyter.de/v2/gh/helmholtz-analytics/heat/HEAD?system=deNBI-Cloud&flavor=m1) |
| Social sciences / Political science | **AMMICO** | AI-based analysis of image and video content, including emotional and factual content, for political science and communication research. | [Run on Jupyter4NFDI](https://hub.nfdi-jupyter.de/v2/gh/ssciwr/AMMICO/HEAD?system=deNBI-Cloud&flavor=m1)) |
| Digital humanities | **Sentiment Analysis with Python** | Interactive self-study course using German literary texts, including Grimm's fairy tales, to teach Python, text processing and sentiment analysis. Uses Thebe to execute code in the browser. | [Run on Jupyter4NFDI](https://hub.nfdi-jupyter.de/v2/gh/Bayquiri/python-sentiment-grimm/HEAD?system=deNBI-Cloud&flavor=m1) |
| Materials science / Machine learning | **Symbolic Regression via Compressed Sensing** | Tutorial demonstrating machine learning methods for materials science using a small example dataset (under 100 MB). | [Incubator](https://github.com/NFDI-Jupyter/services/discussions/40) |
| Geophysics / Scientific software | **Issue2Docker / pyGIMLi** | Reproducing scientific software issues in interactive computational environments. Developed and tested using pyGIMLi for geophysical modelling and inversion. | [Run on Jupyter4NFDI](https://hub.nfdi-jupyter.de/v2/gh/gimli-org/pyGIMLi/HEAD?system=deNBI-Cloud&flavor=m1) |
| Metrology / Engineering | **ScanClouDT** | Processing and analysis of terrestrial laser scanning point clouds, including filtering, segmentation, geometry fitting and uncertainty estimation. | [Project](https://www.scancloudt.ptb.de/news-events) |
| Social sciences / Computational methods | **Methods Hub** | Integrating computational training materials and research tools from Methods Hub into Jupyter4NFDI to support reproducible and reusable workflows. | [Launch from libraries](https://methodshub.gesis.org/) |
| Bioinformatics / Computational workflows | **CloWM** | Connecting reproducible computational workflows with Jupyter for interactive post-processing, visualisation and analysis of results stored in S3 buckets. | [Launch with CloWM](https://cmg.pages.ub.uni-bielefeld.de/clowm/clowm-user-documentation/11B_Jupyter) |
| Digital humanities / Text mining | **AVOBMAT** | Multilingual text mining and analysis of bibliographic metadata and textual collections, with support for 24 languages. | [Incubator](https://github.com/NFDI-Jupyter/services/discussions/49) |


These incubator projects provide starting points for developing representative Jupyter4NFDI-ready demonstrations across research domains.


## Resources

For documentation and further information, see [nfdi-jupyter.de](https://nfdi-jupyter.de/).
