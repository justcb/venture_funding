# Venture Funding with Deep Learning

This Colab worksheet uses a deep learning neural network to predict which businesses will ultimately be successful.  The project starts with data on approximately 34,000 organizations.  It then creates three models to evaluate the test data.  Ultimately, the model is accurate approximately 74% of the time.

# Imports

To run, this worksheet imports the following:

- import pandas as pd
- from pathlib import Path
- import tensorflow as tf
- from tensorflow.keras.layers import Dense
- from tensorflow.keras.models import Sequential
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import StandardScaler,OneHotEncoder

# Use

Initially, the worksheet pulls in the data from a CSV file stored on GitHub.  Next, using OneHotEncoder, the file converts categorical data to numberical data to assist in evaluation.  The data is then scaled using StandardScaler.  Then the original and two alternative models are created.  The models are saved as HDF5 files in the root directory.

# Collaborators 

This project is a part of the Rice University FinTech bootcamp.

# License

This file is created under the MIT License.
