Mega-Sena
=========

The Mega-Sena is the highest paying lottery in South America and all drawing results are publicly available on the [official website](http://loterias.caixa.gov.br/wps/portal/loterias/landing/megasena/).

<p align="center">
    <img alt="Ballot" src="ballot.jpg">
    <br />
    <a href="https://commons.wikimedia.org/wiki/File:Volante_da_Megasena.jpg" target="_blank">
        Mega-Sena ballot
    </a>
</p>


## Goals

The goals of this project are:

* Extract, transform and clean the raw data `(1 - Data Extraction.ipynb)`;

* Perform statistical analysis on the dataset `(2 - Statistical Analysis.ipynb)`;

* Implement an interactive plot in a Jupyter notebook`(3 - Interactive Plot.ipynb)`.

<p align="center">
    <img alt="Interactive Plot" src="interactive_plot.gif">
    <br />
    <a href="https://github.com/victorjnpires/Mega-Sena/blob/master/3%20-%20Interactive%20Plot.ipynb" target="_blank">
        Interactive Plot
    </a>
</p>

This project was last updated on 2019-04-16, bringing higher resolution plots and the most recent dataset.


## Data Sources

* [Mega-Sena official website](http://loterias.caixa.gov.br/wps/portal/loterias/landing/megasena/)


## Installation

To create a new virtual environment with Anaconda:

    $ conda create --name <VENV_NAME> jupyter lxml matplotlib numpy pandas seaborn


## Running

First open a terminal on the project folder and switch the Anaconda virtual environment:

    $ conda activate <VENV_NAME>

Then run the Jupyter notebook server:

    $ jupyter notebook


# Author

Victor Jose Novaes Pires

[https://victorjnpires.github.io/](https://victorjnpires.github.io/)
