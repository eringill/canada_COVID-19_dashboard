Canada COVID-19 Dashboard
=========================

Motivation
----------

This is a data science / data visualization project that I am undertaking in my spare time in order to learn bokeh and refine my python skills. This is very much a work in progress. The purpose of the dashboard is for users to be able to explore **Canadian COVID-19** data in an interactive manner. 

In order to access the dashboard, click on the button below, then click on the file `"main.ipynb"`. Execute the code, and you'll be able to interact with live data.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eringill/Canada_COVID-19_Dashboard/fd79b76)

Data Source
-----------
The dashboard downloads data on a daily basis from [Canada's Health Infobase]("https://health-infobase.canada.ca/src/data/covidLive/covid19.csv"). The data are live, and updated daily by the Canadian Government.

Required Libraries
------------------
You don't need any libraries installed to run the binder from the link above. If you want to run the notebook on your own computer, you'll need to install:
* python
* pandas
* bokeh
* math

Files
-----
* README.md - This file
* LICENSE.md - Legal information
* main.ipynb - the jupyter notebook that contains the code for the dashboard
* environment.yml - the environment file that is required to build the docker image for the binder so the dashboard can be run online
* Canada_COVID-19_Dashboard.html - a (non-live) file that can be viewed in a web browser as an example

Results
-------
This project is all about users interacting with the data and drawing their own conclusions. Have a look and see what you can discover about
the COVID-19 situation in Canada right now.



