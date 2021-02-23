# SAME - The New PropTech In Town

![](Images/logo.png)

SAME is a PropTech startup disrupting the way real estate investing is done. The world that we live in is changing, and with change comes great responsibility. Responsibility that requires innovation, which is the core of our business model. We make recommendations to our users based on their lifestyle and their financial goals. 

Our goal is to leverage our data-driven business model to educate and empower our users around Real Estate Investing. We provide users the research and analysis needed to decide whether you should sell, buy, or rent out a property. We are in an information era and knowledge is key. Which is why we are seeking a $250,000 (or 5 bitcoins) investment for 10% stake in our company, allowing us to give our  customers the key to investing in real estate, or the key to their next home. 


---

## Technologies

This project leverages python 3.7 with the following packages:

* [Pandas](https://pandas.pydata.org/) - For data cleaning, preparation and manipulation

* [Fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint

* [Questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

* [Pyviz](https://pyviz.org/) - Python visualization package that provides a single platform for accessing multiple visualization libraries. Two of these libraries are Plotly Express and hvPlot, which were used in this project

* [The Mapbox API](https://account.mapbox.com/auth/signup/) - To use the Mapbox API, you need to register for a public Mapbox API access token

* [SQLAlchemy](https://www.sqlalchemy.org/) - An open-source SQL library for Python. It’s designed to ease the communication between Python-based programs and databases

* [Flask](https://flask.palletsprojects.com/en/1.1.x/) - A Python library which allows you to build a web application


---

## Installation Guide

Download Anaconda for your operating system and the latest Python version, run the installer, and follow the steps.

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
  pip install pytest
```

To install PyViz and its dependencies in your Conda dev environment, complete the following steps:

1. From your terminal, log in to your Conda dev environment.

2. Install the PyViz packages by using the conda install command as follows:
    
	conda install -c plotly plotly=4.13.
    conda install -c pyviz hvplot

To confirm that SQLAlchemy installed in your Conda dev environment, open a terminal window, and then complete the following steps:
    
	conda list sqlalchemy


---

## Usage

After collecting and preparing the data, you should see the following:


The command line interface shows the following:


The final outcome should result in the following:

- A Jupyter notebook with an analysis and recommendation of the best city for the user's real estate investment

- Professionally styled and formatted interactive visualizations


---

## Contributors

Brought to you by Samual Prutton, Aruna Bisht, Matheus Araujo, Edgar Coronado

