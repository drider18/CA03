# CA03

This program was designed to create a decision tree in order to determine the income level of people. 
This was done through using a train and test dataset to train our model. This would then enable us to 
use certain parameters to determine what the income level would be for our subject and we could state the
accuracy of this prediction as well. 

The packages we needed are stated below:

import numpy as np
import pandas as pd

import matplotlib.pyplot as plt
%matplotlib notebook
%matplotlib inline
import seaborn as sns

!pip install six
from six import StringIO

from sklearn.preprocessing import LabelEncoder
from sklearn.tree import DecisionTreeClassifier

from IPython.display import Image  
import graphviz
from sklearn.tree import export_graphviz
import pydotplus
from sklearn import metrics
from sklearn.metrics import accuracy_score
from sklearn.metrics import classification_report
from sklearn.metrics import confusion_matrix
from sklearn.metrics import f1_score
from sklearn.metrics import precision_score
from sklearn.metrics import recall_score
from sklearn.metrics import roc_auc_score
from sklearn.metrics import roc_curve


In order to download the data I used google drive and imported drive. We then have to 
mount our document to our drive. Lastly, in order to read in the data we simply 
connect it to our Colab Notebooks and then we are ready to connect to our data 
and perform our analysis. 

After we get our data we then perform our analyses and determine what a good model might be. 
After determining our best model, we then need to apply the final parameters to our data to get
our final decision. With the parameters stated we determined that the income level for such a person
would be equal to or below $50k. The confidence of this prediction was 72%















