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

#### Optional download

Ignore the next line if the connection is too slow:

```sh
python -m spacy download en_core_web_lg
```


### Start notebook

```sh
jupyter notebook
```

# Resources

![Hands-On Machine Learning with scikit-learn and Scientific Python Toolkits](https://github.com/gr33ndata/[reponame]/blob/[branch]/image.jpg?raw=true)

- Hands-On Machine Learning with scikit-learn and Scientific Python Toolkits [Amazon ES](https://www.amazon.es/Machine-Learning-scikit-learn-Scientific-Toolkits/dp/1838826041)

- Adyen Blog


# Contact me 

Tarek Amr <tarekamr@gmail.com>




