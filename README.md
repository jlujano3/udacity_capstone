# udacity_capstone

## Libraries used
This project takes advantage of standard libraries. Ensure you have these before starting your journey.

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import datetime as dt

from sklearn.preprocessing import StandardScaler, MinMaxScaler
from sklearn.decomposition import PCA
from sklearn.cluster import KMeans
from sklearn.ensemble import GradientBoostingClassifier
from sklearn.pipeline import Pipeline
from sklearn.model_selection import GridSearchCV

## Project overview
This project starts with an analysis of Bertelsmann / Arvato's customer base in relation to the German population. This comparison involves two datasets customers.csv and azdias.csv which will represent the customers of arvato and the German population, respectively. You can find out more about the way I tackled the problem in my medium blog post. The second part of the project leverages findings from the first part of the project to build a model to predict response to a mailing campaign.
