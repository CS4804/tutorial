# Tutorial
This tutorial aims to help you setup develop environments for CS 4804 programming assignments.

## Python Installation
* Python for [Windows](https://www.python.org/downloads/windows/)
* Python for [Linux/UNIX](https://www.python.org/downloads/source/)
* Python for [Mac OS X](https://www.python.org/downloads/mac-osx/)
* [Anaconda Individual Edition](https://www.anaconda.com/products/individual)

ps. Please use Python 3.6 for class assignments

## Inatall Anaconda3 using Docker
* [Docker installation](https://docs.docker.com/get-docker/)
```
docker search continuumio
docker pull continuumio/anaconda3
docker images
```
* Run Anaconda3
```
docker run -t -i continuumio/anaconda3 /bin/bash
docker run -ti -v /Path/tutorial:/tutorial continuumio/anaconda3 /bin/bash
```

## Setup Python env using conda
* Create a Python 3.6 env
```
conda create --name cs4804 python=3.6
conda env list
```
* Activate an env
```
conda activate cs4804
```
* Deactivate an env
```
conda deactivate
```
* Install Python libraries
```
conda search beautifulsoup4
conda install beautifulsoup4
conda list | grep beaut
```
