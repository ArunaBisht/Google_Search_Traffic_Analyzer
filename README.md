# Google Search traffic analysis
With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. Through this we are analyzing the company's financial and user data in clever ways to make the company grow. The objective is to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock

## Technologies

This project leverages python 3.7 with the following packages:

* [Pandas](https://pandas.pydata.org/) - For data cleaning, preparation and manipulation

* [Jupyter Notebook](https://jupyter.org/) - An open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

* [Visual Studio Code](https://code.visualstudio.com/) - A code editor redefined and optimized for building and debugging modern web and cloud applications

## Installation Guide

Download Anaconda for your operating system and the latest Python version, run the installer, and follow the steps.

Before running the application first install the following dependencies.

```python

  pip install pandas
  pip install sklearn
  pip install imblearn
  pip install hvplot
```

To install PyViz and its dependencies in your Conda dev environment, complete the following steps:

1. From your terminal, log in to your Conda dev environment.

2. Install the PyViz packages by using the conda install command as follows:
    
	conda install -c plotly plotly=4.13.
    
    conda install -c pyviz hvplot
-----------------------------------------------------------------------------------------------------------------------------------------------------

## Usage


Classification matrix - this shows both 'healthy loan' and 'high risk loans' are good but stronger in prediciting 'healthy loans' and slightly weaker in predicting 'high risk loan'

![](snapshots/classification_matrix.png)

----------------------------------------------------------------------------------------------------------------------------------------------------

Classification matrix after resampling 

![](snapshots/re-sampling.png)

-----------------------------------------------------------------------------------------------------------------------------------------------------

.
## Contributors
Done by me Aruna
