# How to run the SPICE tutorial


## You can run this notebook in Google Colab:
You can also run this notebook with Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ISRO-ESA-Heliophysics-Workshop/hands-on-materials/blob/main/solar-orbiter/spice/sospice-demo.ipynb)

## Or locally on your machine
From within a new environment:
```sh
python -m venv venv
. venv/bin/activate
python -m pip install -r requirements.txt
```
This will also install the `jupyter` package. Then, still within the environment, install it for Jupyter with
```
ipython kernel install --user --name=spice-demo-isro
```
and run
```
jupyter notebook
```
or
```
jupyter-lab
```
then open this notebook and run it with the kernel `spice-demo-isro`.

## You can run this notebook in Google Colab:
You can also run this notebook with Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ISRO-ESA-Heliophysics-Workshop/hands-on-materials/blob/main/solar-orbiter/spice/sospice-demo.ipynb)


and you will need to include this at the start of the Google Colab notebook:
```!pip -q install -r https://raw.githubusercontent.com/ISRO-ESA-Heliophysics-Workshop/hands-on-materials/refs/heads/main/solar-orbiter/spice/requirements.txt```

