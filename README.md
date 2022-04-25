# From Zero to Natural Language Processing Hero 

Workshop materials for my [From Zero to Natural Language Processing Hero Workshop](https://jonthebeach.com/workshops/From-Zero-to-Natural-Language-Processing-Hero) at [J on the Beach 2022](https://jonthebeach.com/)

> Ever wondered how your email identifies spam messages? How does news applications classify news into topics? Or how does Google translate detect the language of a page? In this session we will explore the theory foundations behind natural language processing. Then we will, step by step, build a machine learning solution that automatically classifies text messages. 

# Preparing your machine

### Install Miniforge 

Pick the right installer for your machine from [this link](https://github.com/conda-forge/miniforge) 


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

First, go to the `jonthebeach` directory:

```sh
cd jonthebeach
```

Let's now create a new environment. Good practice, to keep your computer clean:

```sh
conda create --name jotb python=3.9
```

et's now activate the environment we have just created:

```sh
conda activate jotb
```

Install the needed requirements:

```sh
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

![Hands-On Machine Learning with scikit-learn and Scientific Python Toolkits](/img/Machine-Learning-Scikit-Learn-Book.jpeg)

- Hands-On Machine Learning with scikit-learn and Scientific Python Toolkits [Amazon ES](https://www.amazon.es/Machine-Learning-scikit-learn-Scientific-Toolkits/dp/1838826041)

- Adyen Tech Blog [Adyen.com/Blog](https://www.adyen.com/blog/category/tech?category=tech)
- J on the Beach [Malaga, Spain. 27th-29th April 2022](https://jonthebeach.com/)

# Join Adyen

![Adyen payment platform](/img/adyen-logo.png)

Adyen is always looking for clever people like you.

[Check our open positions here](https://careers.adyen.com/)

# About me

Tarek Amr is a Senior Machine Learning Scientist at [Adyen](https://www.adyen.com/). Before Adyen, Tarek worked for marketplaces such as [Catawiki](https://www.catawiki.com/) and [TicketSwap](https://www.ticketswap.com/), where he built end-to-end data solutions and predictive models. Tarek has published a couple of books on machine learning and data visualization. His most recent book is “[Hands-On Machine Learning with Scikit-Learn and Scientific Python Toolkits](https://www.packtpub.com/product/hands-on-machine-learning-with-scikit-learn-and-scientific-python-toolkits/9781838826048)”. Tarek holds an MSc. in Computer Science from the [University of East Anglia](https://www.uea.ac.uk/), with focus on algorithms, information retrieval and natural language processing. 

Tarek Amr @[gr33ndata](https://twitter.com/gr33ndata)




