# deep-learning-challenge
Module 21 challenge

## Requirements

### Preprocess the Data (30 points)
- Create a dataframe containing the charity_data.csv data, and identify the target and feature variables in the dataset (2 points)
- Drop the EIN and NAME columns (2 points)
- Determine the number of unique values in each column (2 points)
- For columns with more than 10 unique values, determine the number of data points for each unique value (4 points)
- Create a new value called Other that contains rare categorical variables (5 points)
- Create a feature array, X, and a target array, y by using the preprocessed data (5 points)
- Split the preprocessed data into training and testing datasets (5 points)
- Scale the data by using a StandardScaler that has been fitted to the training data (5 points)

### Compile, Train and Evaluate the Model (20 points)
- Create a neural network model with a defined number of input features and nodes for each layer (4 points)
- Create hidden layers and an output layer with appropriate activation functions (4 points)
- Check the structure of the model (2 points)
- Compile and train the model (4 points)
- Evaluate the model using the test data to determine the loss and accuracy (4 points)
- Export your results to an HDF5 file named AlphabetSoupCharity.h5 (2 points)

### Optimize the Model (20 points)
- Repeat the preprocessing steps in a new Jupyter notebook (4 points)
- Create a new neural network model, implementing at least 3 model optimization methods (15 points)
- Save and export your results to an HDF5 file named AlphabetSoupCharity_Optimization.h5 (1 point)

### Write a Report on the Neural Network Model (30 points)
- Write an analysis that includes a title and multiple sections, labeled with headers and subheaders (4 points)
- Format images in the report so that they display correctly (2)
- Explain the purpose of the analysis (4)
- Answer all 6 questions in the results section (10)
- Summarize the overall results of your model (4)
- Describe how you could use a different model to solve the same problem, and explain why you would use that model (6)

---

## Summary

This assignment involved building a binary classification model to predict the effectiveness of funding provided by Alphabet Soup. Here's what I covered:

### Data Preprocessing:
- Loaded the dataset using Pandas and identified target and feature variables.
- Removed non-beneficial columns and binned rare categorical variables.
- Encoded categorical variables and split the data into training and testing datasets.
- Scaled the data for uniformity.

### Model Development:
- Designed a neural network model using TensorFlow and Keras.
- Compiled, trained, and evaluated the model, exporting it to an HDF5 file.

### Optimization:
- Explored techniques to improve the model's performance, such as adjusting architecture and optimization parameters.

### Report Writing:
- Summarized the analysis, including an overview, results, and recommendations.

### Markdown Formatting:
- Demonstrated Markdown cell usage in Jupyter Notebook for documentation.

---

## Documentations

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [TensorFlow Documentation](https://www.tensorflow.org/learn)
- [Keras Documentation](https://keras.io/guides/)
- [Markdown Guide](https://www.markdownguide.org/)

---

## References beyond the class recordings
- [Categorical Encoding in Pandas](https://pbpython.com/categorical-encoding.html)
- [Save and Load Models in TensorFlow/Keras](https://www.tensorflow.org/tutorials/keras/save_and_load)
