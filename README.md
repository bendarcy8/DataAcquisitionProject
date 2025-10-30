# DataAcquisitionProject
Data Acquisition Project – Kaggle dataset + Web Scraping
# The first thing I did was mount my google drive to colab and then import pandas and other packages.
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import requests
from bs4 import BeautifulSoup

# I then read my csv file into google colab and read the first few rows to make sure the file was imported and also familiarizing mysefl with the column headers and values.
# This dataset contains data from 2015-2022 of player information such as performance statistics and results from tournaments.
df = pd.read_csv("/content/ASA All PGA Raw Data - Tourn Level.csv")
df.head()

