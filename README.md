====================================================================
            TITANIC DATASET ANALYSIS
        USING PANDAS SERIES AND DATAFRAMES
====================================================================


PROJECT OBJECTIVE
--------------------------------------------------------------------

The objective of this project is to analyze the Titanic passenger
dataset using the Pandas library.

Students will apply core Pandas concepts such as Series and
DataFrames, data cleaning, indexing, filtering, sorting,
grouping, merging, and importing/exporting data to extract
meaningful insights about passenger survival patterns.



TECHNOLOGIES USED
--------------------------------------------------------------------

Python
Pandas
NumPy
Jupyter Notebook / Google Colab



PROJECT WORKFLOW
====================================================================


1️⃣ DATA IMPORT
--------------------------------------------------------------------

Imported dataset using pd.read_csv()



2️⃣ SERIES AND DATAFRAME CREATION
--------------------------------------------------------------------

Created DataFrame from dataset

Extracted Series for:
- Age
- Fare
- Survived



3️⃣ DATA INSPECTION
--------------------------------------------------------------------

Used:
- head()
- info()
- describe()



4️⃣ HANDLING MISSING DATA
--------------------------------------------------------------------

Identified missing values using isnull()

Filled missing values:
- Age → Mean
- Embarked → Mode

Dropped Cabin column (too many missing values)



5️⃣ INDEXING AND SLICING
--------------------------------------------------------------------

Used:
- .loc[]
- .iloc[]

Extracted selected columns for analysis



6️⃣ RENAMING AND RESHAPING
--------------------------------------------------------------------

Renamed column:
Sex → Gender

Used pivot_table() for structured analysis



7️⃣ FILTERING AND SORTING
--------------------------------------------------------------------

Filtered passengers based on:

- Age > 30
- Fare > 50
- Female passengers who survived

Sorted data by:
- Fare
- Age
- Survival status



8️⃣ GROUPING AND AGGREGATION
--------------------------------------------------------------------

Performed analysis using groupby():

- Survival rate by Gender
- Average Age by Passenger Class
- Survival count by Embarked location



9️⃣ MERGING, JOINING, AND CONCATENATION
--------------------------------------------------------------------

Created additional DataFrame

Applied:
- merge()
- concat()



🔟 CALCULATIONS AND INSIGHTS
--------------------------------------------------------------------

Calculated:

- Average age of survivors vs non-survivors
- Highest and lowest fare paid
- Overall survival percentage



LEARNING OUTCOMES
====================================================================

After completing this project, students will understand:

- Practical implementation of Pandas
- Real-world dataset cleaning
- Data analysis workflow
- Extracting meaningful insights from structured data

====================================================================
