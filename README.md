Jupyter Notebooks and Associated Public Content 2019
===

## Launch the Notebooks Interactively. Click here => [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TheZetner/jupyter-examples-2019/master)

[Binder](https://gke.mybinder.org/) is a service that turns a Git repo into a collection of interactive notebooks.  
You'll enjoy the experience of Jupyter Dashboard and notebooks in the cloud.

## Local users on JupyterHub - download notebooks using Jupyter Terminal
* Sign in at [https://jupyter.cscscience.ca](https://jupyter.cscscience.ca) with Science Network user/password
* Click the '+' in the upper left, scroll down to _Other_
* Open a Terminal and enter the below command to download and make available the notebooks:  
```wget --content-disposition "https://github.com/TheZetner/jupyter-examples-2019/archive/v0.2.zip" -O jupyter.zip; unzip jupyter.zip; while read p; do pip install --user $p; done < jupyter-examples-2019-0.2/requirements.txt```
* Sometimes jupyter hub can have issues like _File load errors_ (it's not a core resource and has no designated IT staff) but the easiest way to fix those is to open up a jupyter terminal as above and kill your user's processes on jupyter then refresh the page and follow the prompts: ```killall -u YOURSCIENCEUSERNAME```

---
## Run the notebooks on [Microsoft Azure](https://notebooks.azure.com/TheZetner/projects/jupyter-examples-2019)

Azure is a similar service as Binder allowing the user to run jupyter notebooks with a limited number of kernels.

---

## See the [Gists](https://gist.github.com/TheZetner) 
* Gists are single files, parts of files, and full applications to easily share with other people. 
* Directories can't be shared 
* Gists can be public or private
* Gists are editable in place
* Gists are repositories that can be forked and cloned
* [More about Gists](https://help.github.com/en/articles/about-gists)

## Example Jupyter Notebook with R: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/r/master?filepath=index.ipynb)

[Repository](https://github.com/binder-examples/r)

---

## Leave Feedback and View the [Slides](https://forms.gle/MTRRMaa3ScVGNWYu9)
Slides are available after the workshop as thanks for filling out the feedback form!

---

## Other Resources
Please don't read these while I present. I'll definitely know </3.

### Reproducibility
*   [Nature article on reproducibility](https://www.nature.com/news/1-500-scientists-lift-the-lid-on-reproducibility-1.19970)
*   [More recent Nature article on Jupyter as a data science tool](https://www.nature.com/articles/d41586-018-07196-1)
*   [Reproducible Research](https://github.com/Reproducible-Science-Curriculum/introduction-RR-Jupyter/blob/gh-pages/notebooks/Intro-to-reproducible-research.ipynb)


### Markdown 

*   [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) Cheatsheet
*   [Markdown, the Jupyter guide](https://medium.com/ibm-data-science-experience/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed)


### Data Science

*   [The unreasonable effectiveness of public work - David Robinson](https://resources.rstudio.com/rstudio-conf-2019/the-unreasonable-effectiveness-of-public-work)
*   [I don’t like notebooks - Joel Grus](https://docs.google.com/presentation/d/1n2RlMdmv1p25Xy5thJUhkKGvjtV-dkAIsUXP-AL4ffI/edit#slide=id.g37ce315c78_0_13)
*   [Eliademy: Open Research Software and Open Source](https://eliademy.com/catalog/oer/module-5-open-research-software-and-open-source.html)
*   [DOI Numbers and Citable Code with Github](https://guides.github.com/activities/citable-code/)
*   [Open source licenses](https://opensource.org/licenses)


### Jupyter Links

*   [Online resources](https://www.dataschool.io/cloud-services-for-jupyter-notebook/#howtochoosetherightserviceforyou) to run jupyter
*   [Jupyter Project home](https://jupyter.org/)
*   [10 Rules for working in jupyter notebooks](https://github.com/jupyter-guide/ten-rules-jupyter)
*   [Combining interactivity and reproducibility: Can Jupyter Notebooks Serve Two Masters? Amanda Birmingham](http://compbio.ucsd.edu/wp-content/uploads/2018/07/20180405_can_jupyter_notebooks_serve_two_masters_flattened.pdf)
*   [Jupyter project and notebook organization](https://pbpython.com/notebook-process.html)


### Jupyter Sources

*   [https://www.dataquest.io/blog/jupyter-notebook-tutorial/](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)
*   [https://www.slideshare.net/lynnlangit/jupyter-notebooks-by-bioinformatics-examples](https://www.slideshare.net/lynnlangit/jupyter-notebooks-by-bioinformatics-examples)
*   [https://reproducible-science-curriculum.github.io/publication-RR-Jupyter/](https://reproducible-science-curriculum.github.io/publication-RR-Jupyter/)
*   [https://github.com/jupyter-guide/ten-rules-jupyter](https://github.com/jupyter-guide/ten-rules-jupyter)
*   [https://github.com/jupyter-guide/jupyter-guide](https://github.com/jupyter-guide/jupyter-guide)

### Jupyter Lab

*   Jupyter’s Next-Generation Notebook Interface: [LINK](https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906)
*   JupyterLab is a web-based interactive development environment for Jupyter notebooks, code, and data.
*   JupyterLab is flexible: configure and arrange the user interface to support a wide range of workflows in data science, scientific computing, and machine learning. 
*   JupyterLab is extensible and modular: write plugins that add new components and integrate with existing ones.
*   Activate in binder file explorer by changing end of url from ```/tree``` to ```/lab```

### Notebook Extensions

![Notebook Extensions](https://miro.medium.com/max/1000/1*hRhdOuS-4NxEyd4Yqlzwxg.png)
*   [Notebook Extensions](https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231)
*   Enable nbextensions  
    ```conda install -c conda-forge jupyter_nbextensions_configurator```
*   Enable nbextensions  
    ```jupyter nbextensions_configurator enable --user```
*   Make Repo for notebooks, [get personal access token from github](https://help.github.com/en/articlescreating-a-personal-access-token-for-the-command-line)
*   Go to Nbextensions tab on dashboard
*   Activate GIST-IT, add your access token
*   Click gistit button on notebook

* An interesting looking extension to track exploration history: https://github.com/mkery/Verdant
