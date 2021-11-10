# STA 9760 - Project 2
### Brendan Philbin, 11/24/2020

## 1. Introduction
### Dataset Source

The basis of this project, as seen in the supplemental jupyter notebook, is to import and analyze 9.7gb of Yelp review data. The datasets come from Kaggle, and are available using the following link:
https://www.kaggle.com/yelp-dataset/yelp-dataset

### Software Used
In order to analyze this data, I launched an Apache Spark cluster via AWS. I leveraged the power of this cluster inside of a jupyter notebook, using Pyspark. The notebook, ("Analysis.ipynb"), contains all of the necessary code to run this script. Several python modules were needed to run this analysis, and were installed at the beginning of the notebook (Matplotlib, Pandas, Seaborn).



#### Quick note about code

During the analysis, a small chunk of code was used to normalize/scale the rating skewness before passing it through a visualization. For reference, the code to do this was found on Stack Overflow.

Link: https://stackoverflow.com/questions/40337744/scalenormalise-a-column-in-spark-dataframe-pyspark



### Cluster Configuration

![cluster_image](assets/cluster_configuration.png)

### Notebook Configuration
![notebook_image](assets/notebook_configuration.png)

## 2. Analysis
The supplied code provides written and visual answers to the following questions:

	- How many unique business categories are contained in the dataset?
	- What are the most common categories in the dataset?
	- What is the average "star" rating for each business?
	- Do these ratings skew in a negative bias?
	- For users that carry an "elite" ranking, how do their star ratings compare to the average ranking for all users?

## 3. Contact Me
For any follow-up questions, please contact me at:

BRENDAN_PHILBIN@baruchmail.cuny.edu



