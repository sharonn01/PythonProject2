**Titanic Dataset Analysis Using Pandas Series and DataFrames**

**Project Objective**
The objective of this project is to analyze the Titanic passenger dataset using the Pandas library. Students will apply core Pandas concepts such as Series and DataFrames, data cleaning, indexing, filtering, sorting, grouping, merging, and importing/exporting data to extract meaningful insights about passenger survival patterns.

**Technologies Used**
Python
Pandas
NumPy
Jupyter Notebook / Google Colab

**Project Workflow**
**1️⃣ Data Import**
Imported dataset using pd.read_csv()

**2️⃣ Series and DataFrame Creation**
Created DataFrame from dataset
Extracted Series for Age, Fare, and Survived columns

**3️⃣ Data Inspection**
Used:
head()
info()
describe()

**4️⃣ Handling Missing Data**
Identified missing values using isnull()
Filled missing values:
Age → Mean
Embarked → Mode
Dropped Cabin column (too many missing values)

**5️⃣ Indexing and Slicing**
Used:
.loc[]
.iloc[]
Extracted selected columns

**6️⃣ Renaming and Reshaping**
Renamed column Sex → Gender
Used pivot_table() for analysis

**7️⃣ Filtering and Sorting**
Filtered passengers based on:
Age > 30
Fare > 50
Female passengers who survived
Sorted data by:
Fare
Age
Survival status

**8️⃣ Grouping and Aggregation**
Performed analysis using groupby():
Survival rate by Gender
Average Age by Passenger Class
Survival count by Embarked location

**9️⃣ Merging, Joining, and Concatenation**
Created additional DataFrame
Applied:
merge()
concat()

**🔟 Calculations and Insights**
Calculated:
Average age of survivors vs non-survivors
Highest and lowest fare paid
Overall survival percentage

**Learning Outcomes**
After completing this project, students will understand:
Practical implementation of Pandas
Real-world dataset cleaning
Data analysis workflow
Extracting meaningful insights from structured data
