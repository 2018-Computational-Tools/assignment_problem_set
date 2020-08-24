# Welcome

This is the binder configuration for this problem set. 

> If you are launching this problem set in Jupyter, please navigate to the project directory in the file navigation window on the left.

> If you are launching this problem set in RStudio, please navigate to the project directory in the file navigation window on the right and click on the `project.Rproj` file to launch the problem set.

Everything hereafter is only relevant if you are the person maintaining this problem set.

# Setup

This branch should only contain a [`binder`](binder/) directory with the configuration files. Only make changes in this branch if you need to add additional R or python dependencies. Notebooks should go into the `master` branch instead. If you DO change this branch, make sure to test-launch your binder to initialize setup as it will take a while to launch the first time (~10 minutes up to 2 hours) but then will be fast to launch for everyone else afterwards.
