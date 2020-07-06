# DeepFin Investor Virtual Tutorial: Spatial Data Science with CARTO

This repository contains the material for the DeepFin Investor Virtual Tutorial: Spatial Data Science with CARTO. It includes

- a deck with the slides used during the workshop
- two jupyter notebooks used for the practical session

## Installation requirements

To run the notebooks, please follow the instructions below.

1. Download or clone this repository. To download the repository click the **Code** button and **Download ZIP**. Otherwise, if you have git installed, you can clone it.

  ```bash
  $ git clone git@github.com:CartoDB/jpm_deepfin_investor_workshop.git
  $ cd data-science-book
  ```
  
3. Install python (follow instructions here: https://docs.anaconda.com/anaconda/install/) and jupyter notebooks (follow instructions here: https://jupyter.readthedocs.io/en/latest/install.html)

3. Open your terminal, go to the **jpm_deepfin_investor_workshop folder** and run 
  ```bash
  $ jupyter notebook
  ```

4. This will open a new window in your browser, where you will see two jupyter notebooks for the practical session

	- JPMorgan_demo1.ipynb (**Site selection**): where should Starbucks open new coffee shops in Long Island, NY? In this demo we will go through a typical site selection use case, from modelling the revenues of the existing stores as a function of socioeconomic covariates, to predicting the potential revenues in new locations.  

	- JPMorgan_demo2.ipynb (**Logistic spatial optimization**): where should a parcel delivery company locate their distribution and fulfilment centers? What areas should they service? In this demo we will go through a supply chain network optimization use case, from analysing past data to identify spatio-temporal patterns to building an optimization model to analyze and quantify the impact of changes in the current network.

## How to access your CARTO account

1. Go to https://carto.com/login

2. Enter your username and password and click Log In. You will be prompted to your CARTO dashboard

3. Click on the icon on the top right corner, and then on API Keys to visualize your Master Key. To run the demos during the practical session you will only need your username and API Key. For more details, please check this video

![](access.gif)

4. Once you have your credentials, you can then start using CARTO:

	- CARTO Builder: load data and create beautiful maps directly from your Dashboard.
	https://carto.com/help/tutorials/getting-started-with-carto-builder/

	-  CARTOframes: A Python package for integrating CARTO maps, analysis, and data services into data science workflows.
	https://carto.com/developers/cartoframes/
	 


