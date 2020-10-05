# Calculating correlation and skill score on C3S seasonal forecasts

You can test the code in two ways: through Google Colab or locally on your machine. 

The Google Colab notebook shows an example of a workflow involving multiple python modules to calculate on-the-fly (more or less) correlation and probabilistic skill scores on a seasonal forecast downloaded by the [Copernicus Climate Data Store](https://cds.climate.copernicus.eu/#!/home)

The Google Colab notebook [can be explored here](https://colab.research.google.com/drive/1wWHz_SMCHNuos5fxWRUJTcB6wqkTJQCR#scrollTo=bh7W_TKIbzs3)

Locally, you can install the anaconda environment with:
`conda env create -f requirements.yml`

and then run the notebook with Jupyter. 

## Note
We use the version 0.7.1 of the module `esmpy` due to a bug arising in the regridding when using the version 8. See [https://github.com/JiaweiZhuang/xESMF/issues/85](here).


