**Script of Scripts (SoS)** is a lightweight workflow system that helps you organize your commands and scripts in different languages into readable workflows that can be easily understood and modified by others. It is an easy-to-use alternative to specialized workflow systems such as [CWL](http://www.commonwl.org/) which makes it an ideal tool for the creation and maintenance of workflows that need to be frequently updated and shared with others.

Compared to maintaining multiple scripts, or using more specialized workflow languages (e.g. [CWL](http://www.commonwl.org)) or systems such as [YAWL](http://www.yawlfoundation.org/) and [Galaxy](https://galaxyproject.org/), or make-file style workflow system such as [snakemake](https://bitbucket.org/johanneskoester/snakemake), 

* **SoS offers a way to organize your scripts in a single file**, which makes it easy to execute and maintain. You can include small and frequently changed commands and scripts in SoS and keep large and stable scripts in separate files.
* **SoS scripts are human readable and writable**. The workflow steps are logically arranged and the scripts and commands are kept mostly in their original form so it is easy for others to read a SoS workflow and modify it if needed. It follows [Python](http://www.python.org) syntax which is easy to understand even for users who do not know Python. In comparison, it would take a lot of time and practice to learn a specialized language to write a [CWL](http://www.commonwl.org/) workflow (see [this CWL tutorial](http://www.commonwl.org/v1.0/UserGuide.html) for an example).
* **SoS allows for notebook-, forward- and make-style definitions of workflows**. SoS does not limit you to particular way of defining a workflow. You can use SoS as a notebook to keep track of steps of analysis (notebook-style), transform the notes to a real workflow (forward-style), and add dependency rules if needed (make-style).
* **You can use SoS interactively with [iPython](https://ipython.org/) or [Jupyter](http://jupyter.org/), write and debug SoS scripts in [Spyder](https://pythonhosted.org/spyder/), and execute scripts in batch mode** with advanced workflow features. The workflow features of SoS are easy to use yet very powerful in helping you execute your pipelines efficiently not only locally, but also on cluster and cloud systems.

SoS, SoS Notebook, and all SoS extensions are distributed under a GNU
Public License (V3) for non-commercial use. Commercial users should [contact
Dr. Bo Peng](email:bpeng@mdanderson.org) for separate commercial licenses. 

