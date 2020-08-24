# Welcome

This is the binder configuration for dual use of R and python in the same project. If you are launching this in RStudio, please navigate manually to the project directory and click on the `project.Rproj` file to launch the project. In Jupyter this happens automatically. 

Everything hereafter is only relevant if you are the person designing this project.

# Setup

This branch should only contain a [`binder`](binder/) directory with the configuration files. Only make changes in this branch if you need to add additional R or python dependencies. Notebooks should go into the `master` branch instead. If you DO change this branch, make sure to test-launch your binder to initialize setup as it will take a while to launch the first time (~10 minutes up to 2 hours) but then will be fast to launch for everyone else afterwards.
