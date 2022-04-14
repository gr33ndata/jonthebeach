# From Zero to Natural Language Processing Hero 

Workshop materials for my workshop at [J on the Beach 2022](https://jonthebeach.com/)


# Preparing your machine

### Install Miniforge 

Pick the right installer for your machine from [here](https://github.com/conda-forge/miniforge) 


### Initialize Conda 

Run the following command on your terminal (shell, command line):

```sh
conda init
```

### Download this repo

Download the code used in this workshop from [this repo](https://github.com/gr33ndata/jonthebeach) using the following command:

```sh
git clone git@github.com:gr33ndata/jonthebeach.git
```

### Create a new environment


```sh
cd jonthebeach
conda create --name jotb python=3.9
conda activate jotb
pip install --upgrade -r requirements.txt
```

### Start notebook

```sh
jupyter notebook
```


