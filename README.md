# Data Science Challenge

For this data science challenge I am provided with a dataset containing mobility traces of ~500 taxi cabs in San Francisco collected over ~30 days. The format of each mobility trace file is the following - each line contains (latitude, longitude, occupancy, time), e.g. (37.75134 -122.39488 0 1213084687), where latitude and longitude are in decimal degrees, occupancy shows if a cab has a fare (1 = occupied, 0 = free) and time is in UNIX epoch format.
The goala of this data science challenge are:

1. To calculate the potential for yearly reduction on CO2 emissions, caused by the taxi cabs roaming without passengers. In your calculation please assume that the taxi cab fleet is changing at the rate of 10% per month (from combustion engine-powered vehicles to electric vehicles). Assume also that the average passenger vehicle emits about 404 grams of CO2 per mile.
2. To build a predictor for taxi drivers, predicting the next place a passenger will hail a cab.

Bonus question:

3. Identify clusters of taxi cabs that you find being relevant.

## Prerequisites

Create and activate a virtual environment for python. We use python 3.6 for this challenge.

```
virtualenv venv -p /usr/local/bin/python3.6
source venv/bin/activate
```

Now install the requirements by running `pip install -r requirements.txt`

### Jupyter Notebook

**NOTE:** All commands should be executed from the root of the repository.

We recommend you to use `jupyter notebook` in order to execute the code step by step and have the ability to interact with the variables. You need to run the following commands in order to launch `jupyter notebook` and be able to access your virtual environment from it:

```
ipython kernel install --user --name=venv
jupyter-notebook
```

### PyCharm

Those who do not have `jupyter notebook` and are IDE fans can use the exported `.py` file in the `src` directory. We assume that you are familiar with the process of linking a virtual environment to a project in PyCharm.



