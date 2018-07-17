# Jupyter Notebooks for UNM Data Commons Project
## Steps to run container
1. Clone this repository
1. Copy any GTex required files to ./jupyter-nb/gtex directory
1. Build the docker image:
```docker build -t unm/jupyter-nb:v1 .```
1. Run the container
```docker run --name jupyter -d -p 8888:8888 unm/jupyter-nb:v1```
