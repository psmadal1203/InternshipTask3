# InternshipTask3
 Task 3: Visualization using Histogram with Python  Excited to share my exploration of Task 3, where I created a histogram to visualize the distribution of data in the Iris dataset using Python. 
# Objective:

    Create a Histogram:
        Visualize the distribution of data in the Iris dataset

Steps Taken:

# 1. Imported Necessary Libraries:
     import pandas as pd 
     import matplotlib.pyplot as plt
     import seaborn as sns

# 2. Loaded the Dataset:
     # Load the Iris dataset
     iris_data = sns.load_dataset('iris')

3. Created a Histogram:
    # Create a histogram using Seaborn
      plt.figure(figsize=(10, 6))
   
      sns.histplot(data=iris_data, x='sepal_length', bins=20, kde=True, color='skyblue')
   
      plt.title('Distribution of Sepal Length in Iris Dataset')
   
      plt.xlabel('Sepal Length (cm)')
   
      plt.ylabel('Frequency')
   
      plt.show()


5. Sepal Length Distribution
