# import libraries
import pandas as pd
import numpy as np
import plotly.express as px
from datar.all import case_when, f, mutate, pivot_wider
from datar import dplyr
import plotly.io as pio
from plotly.offline import init_notebook_mode, plot
init_notebook_mode()
pio.base_renderers="browser"
import matplotlib.pyplot as plt
from IPython.display import Math, Latex
from IPython.core.display import Image
import seaborn as sns

sns.set(color_codes=True)
sns.set(rc={'figure.figsize':(10,6)})
LSMS1=pd.read_csv(r'C:\Users\flavi\Downloads\data for practice\sect11b_harvestw3.csv')
LSMS1.head()
