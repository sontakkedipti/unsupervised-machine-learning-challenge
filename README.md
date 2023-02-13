# Unsupervised-Machine-Learning-Challenge
<br>Description<br>
Using unsupervised learning by fitting data to a model and using clustering algorithms to place data into groups of patients with or without myopia. Then, created a visualization that shares the finding.
Background
You are on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might be distinct groups of patients that would be better to analyze separately. So, your supervisor has asked you to explore this possibility by using unsupervised learning.
You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether<br> the patients can be placed into distinct groups. Then, you’ll create a visualization to share your findings with your team and other key stakeholders.

<br>Part 1: Prepare the Data<br>
1.	Read myopia.csv into a Pandas DataFrame.<br>
2.	Remove the "MYOPIC" column from the dataset.<br>
3.	Standardize the dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.<br>

<br>Part 2: Apply Dimensionality Reduction<br>
1.	Perform dimensionality reduction with PCA. How did the number of the features change?
2.	Further reduce the dataset dimensions with t-SNE and visually inspect the results. To do this, run t-SNE on the principal components, which is the output of the PCA transformation.
3.	Create a scatter plot of the t-SNE output. Are there distinct clusters?<br>

<br>Part 3: Perform a Cluster Analysis with K-means<br>
Create an elbow plot to identify the best number of clusters. Make sure to do the following:<br>
•	Use a for loop to determine the inertia for each k between 1 through 10.<br>
•	If possible, determine where the elbow of the plot is, and at which value of k it appears.<br>

<br>Part 4: Make a Recommendation<br>
<br>Based on your findings, write up a brief (one or two sentences) recommendation for your supervisor in your Jupyter Notebook.<br>

<br>Can the patients be clustered?<br>
•	The data (sample) is inconclusive to determine if the patients can be clustered into whether they have or does not have myopic. There was 618 samples with 14 variables. After scaling the data and reducing the dimensions, the principle component was reduced to 618 sample with 2 components. In the sample, there was 537 that fell in the 0 category and 81 fell into 1 category. If additional dimensions and/or samples were added, the data would likely allow us to show definitive clusters to help determine whether our patients are myopic or not.
<br>If so, into how many clusters?<br>
•	Inconclusive<br>

Myopia Clusters Findings<br>
After Preparing the Data, Applying Dimensionality Reduction using PCA and reducing this further with t-SNE I performed a Cluster Analysis with K-Means model.<br>
•	The optimal number of clusters found is 3.<br>
•	t-SNE had data more spread out and was not helpful in finding clusters.<br>
•	Dataset is too small to make an accurate prediction or for further splitting and training of data.<br>
•	May be using Test and Training to test the models using bigger data set would have helped.<br>

