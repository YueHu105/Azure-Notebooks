Azure Notebooks Overview



•	Introduction
Azure Notebooks is a free hosted service to develop and run Jupyter notebooks in the cloud with no installation. With Azure Notebooks, users can also copy (or "clone") notebooks into their own account for modification or experimentation, which is especially useful for instruction purposes.

•	Features
1.	Each project is limited to 4GB memory and 1GB data to prevent abuse
2.	Notebook servers are guaranteed to exist for at most 8 hours
3.	Available kernels and environments:
Python 2.7 + Anaconda2-5.3.0
Python 3.6 + Anaconda3-5.3.0
Python 3.5 + Anaconda3-4.2.0 (will be deprecated)
R 3.4.1 + Microsoft R Open 3.4.1
F# 4.1.9
4.	Azure notebook also includes extra packages beyond the base distributions. The Python kernels, for example, include the numpy, pandas, scikit-learn, matplotlib, and bokeh libraries. Users could also customize a project to create an environment for all the notebooks in that project
5.	GitHub support: Cloning a Jupyter notebook from GitHub into your Azure Notebooks account creates an independent copy of the notebook. Changes are stored in your Azure Notebooks account only, and don't affect the original GitHub repository.
6.	Give PowerPoint like slideshows where code in slides is executable
7.	Application scenarios: 
Teach a course for hundreds of students
give a webinar online or at a conference without spending time on installation
8.	Pre-configured Jupyter extensions:
RISE: A Jupyter Slideshow Extension (also known as live_reveal)
JupyterLab: A full computational environment for working with Jupyter notebooks.
Altair: A declarative statistical visualization library for Python.
BQPlot: An interactive plotting framework for Jupyter Notebooks
IpyWidgets: Interactive HTML widgets for Jupyter Notebooks.
9.	Users could choose either private or public for the project

•	Limitation
1.	As this is a preview service under development, there is currently a known issue where the Environment.yml setting does not get applied to the project as expected. The project and the Jupyter notebooks within do not load the specified environment file at present.

•	Future
On October 9, 2020 the Azure Notebooks public preview site will be retired and replaced with integrated services from Visual Studio, Azure, and GitHub. 
Several choices:
1.	Notebooks in Visual Studio Code: a free code editor and development platform that you could use locally or connected to remote compute
2.	Visual Studio Codespaces: provides cloud-hosted environments where you could edit your notebooks using Visual Studio Code or your web browser, and store them on GitHub, without needing to install anything on the devices.
3.	Azure Machine Learning: provides an end-to-end machine learning platform to enable users to build and deploy models faster on Azure VM or a shared cluster computing environment.



