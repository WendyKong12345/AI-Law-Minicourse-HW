# AI-Law-Minicourse-HW
## Supreme Court Topic Modeling
### Step 1 Data Collection and Preparation
This step collects opinion data from the Supreme Court website from year 1760 to year 2018.  The code first defines a method that retrieves data from a given link.  It then defines a method that constructs a link for each year and calls the first method with the link.  The code then places the retrieved data into a table with two columns, the first column being the url address and the second column being the docket no.  The code saves the table into a pickle file.
### Step 2 Data Collection and Preparation
This step reads the url addresses from the pickle file from Step 1.  It then retrieves the description of each case based on the url addresses by breaking the table from Step 1 into three small tables.  It then appends the description of each case to the table.  The code saves it into a full project pickle file. 
### Step 3 Data Processing
This step cleans up the case description retrieved from Step 2. It removes state names, case names, common stopwords, people's names, dat of the week, etc. The codes saves the outcome into a full project lemmatized pickle file.
### Step 4 Topic Modeling Methods
### Step 5 Topic Model Application

## Word2Vec Using TensorFlow
