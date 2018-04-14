# BrewAnalysis
Practising ML concepts

## Download and extract the data kaggle dataset using below link
[Beer Recipes] (https://www.kaggle.com/jtrofe/beer-recipes)\

* Download and extract the files to the src/input folder
* Install the docker. [steps here] (https://docs.docker.com/install/linux/docker-ce/ubuntu/)

## Setup

Pull scikit-learn docker

`docker pull smizy/scikit-learn`

Start the docker with the current folder as working folder

`docker run  -p 8888:8888 -v $(pwd):/code  -e PASSWORD=123456 -d smizy/scikit-learn`


