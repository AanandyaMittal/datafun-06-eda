# datafun-06-eda
The seaborn geyser dataset found at https://github.com/mwaskom/seaborn-data/blob/master/geyser.csv contains information about geyser characteristics:

This dataset is used for statistical analysis projects. This project is for performing exploratory data analysis and presenting data stories using Jupyter.

Overall this analysis will investigate the differences between long and short geysers, as well as the difference between waiting and duration time of geysers.

## Dataset Description

The seaborn geyser dataset found at  https://github.com/mwaskom/seaborn-data/blob/master/geyser.csv contains information about geyser characteristics:

Variables:  
duration - The length the geyser lasted  
waiting - The length spent waiting for the geyser to start  
kind - Whether the geyser was long or short  

## How to Install and Run the Project

```shell
cd C:\Users\AanandyaMittal\Documents\
git clone https://github.com/AanandyaMittal/datafun-06-eda
```

## Virtual Environment Instructions for Creation and Activation

On Windows, create a project virtual environment in the .venv folder. 

```shell
py -m venv .venv
.venv\Scripts\Activate
```

## Install Requests

```shell
py -m pip install requests
```

## Freeze Requirements Instructions

```shell
py -m pip install -r requirements.txt
py -m pip freeze > requirements.txt
```


## Git Commands for Adding, Committing, and Pushing

```shell
git add .
git commit -m "add .gitignore, adding cmds to README file"
git push -u origin main
```

## Install Jupyter

```shell
py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy pyarrow
```
