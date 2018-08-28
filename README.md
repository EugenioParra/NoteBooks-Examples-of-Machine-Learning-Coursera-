# NoteBooks-Examples-of-Machine-Learning-Coursera-
Notebook with the examples by google in Coursera

2b. Machine Learning using tf.estimator
In this notebook, we will create a machine learning model using tf.estimator and evaluate its performance. The dataset is rather small (7700 samples), so we can do it all in-memory. We will also simply pass the raw data in as-is.

import datalab.bigquery as bq
import tensorflow as tf
import pandas as pd
import numpy as np
import shutil

print(tf.__version__)
