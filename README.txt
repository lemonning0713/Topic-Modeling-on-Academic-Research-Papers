Anly580 Final Project README
---------------------------------
Files：
1. ANLY 580_Final Report_update.ipynb
Contains project report and codes that generate the LDA output.

2. LSI_Mpdel.ipynb
Contains project report and codes that generate the LSI output.

3. README.TXT
Contains steps which will exactly reproduce the numbers, tables and figures in the report.

4. df_abstract.csv
Raw data file collected using Springer Natural API

5. Anly580_Final Poster.pdf
Final Poster



---------------------------------
Data Collection:

Step 1. 
Import libraries: requests, pandas and tqdm

Step 2.
Define apikey and base, set number of query and number of records each query, initialize the dataframe and counter and run specified number of iterations.

Step 3.
Save the dataframe to csv file as 'df_abstract.csv'.



---------------------------------
Data Cleaning and Preprocessing:

Step 1. 
Import libraries: pandas, nltk, seaborn, matplotlib, re, gensim, collections

Step 2.
Drop NA values

Step 3.
Define preprocessing function by identifying stopwords, removing single characters and numbers, removing prefixed 'Abstract', removing latex, tokenizing and lemmatizing corpus.

Step 4.
Use gensim to add bigram and trigram to the corpus

Step 5.
Create the Inputs of LDA model: Dictionary and Corpus.



---------------------------------
Exploratory data analysis：

Step 1. 
Import libraries: pandas, wordcloud, sklearn, numpy, 

Step 2. 
Generate word cloud.

Step 3.
Define function to plot the 10 most common words.



---------------------------------
Model:

1. Latent Dirichlet Allocation (LDA):

Step 1.
Train LDA model.

Step 2. 
Print output.


Step 3. 
Define functions to visualize the output (6 plots from LDA model).



2. LSI:
Step 1:
Train LSI model.

Step 2:
Visualize LSI result (pie chart and wordcloud).