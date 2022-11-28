# Pandas Series Outline DRAFT

Goals:

* Develop good SEO content and authority on Pandas. For this we'll create several more articles on aspects of Pandas than we have now, and start grouping them in a category
* Develop a five day mini-course as an offering for email subscribers
* Improve the practice question list https://codesolid.com/pandas-practice-examples/.  Offer the solution set as part of course.

## Earlier "outline"

* Pandas introduction (John?)
    * Core classes -  DataFrames and Series.
    * See next topic, I think this is easier to understand with datasets, but many authors focus on creating from dictionaries of lists, etc.
    * Using the tools

* "Pandas DataSets" - perhaps one article covering the following:
    * Downloading and unzipping arbitrary file using urllib or requests, plus python zipfile
    * Seaborn [load_dataset](https://seaborn.pydata.org/generated/seaborn.load_dataset.html) and [get_dataset_names](https://seaborn.pydata.org/generated/seaborn.get_dataset_names.html). 
    * https://scikit-learn.org/stable/datasets/toy_dataset.html

* "Kaggle Datasets" (Full article).  On using Kaggle API to download datasets:  https://www.kaggle.com/docs/api#interacting-with-datasets

* Pandas loading dataframe from various types (this has been done a lot)

* Selecting data in pandas (Beginner to Expert)
    * Relation to indexing. 
    * See [Indexing and Selecting data](https://pandas.pydata.org/docs/user_guide/indexing.html)
    * loc.  iloc.  Others?  SQL Article I have in progress already.
    * [Multi-indexing.](https://pandas.pydata.org/docs/user_guide/advanced.html)

* Data cleaning (one article?)
    * Filling in / handling missing data
    * sklearn has tools for this too?
    * removing duplicates

Data transformation:
    * Vectorized string methods / other string techniques

* Grouping data (already have GroupBy article.  See below.  Anything else?)

* Pivot tables and cross-tabulation A lot of this in McKinney's book under "Data Wrangling: Join / Combine / Reshape".  So:
    * Dataframe.combine
    * Dataframe.merge
    * stack and unstack

* Time series data Pandas - A whole chapter in McKinney.  Several articles possible here?
    * Time deltas
    * Windowing functions?
    * Other material, see for example Pandas [Time Series / Date Functionality](https://pandas.pydata.org/docs/user_guide/timeseries.html)

* [Pandas Data Formats](https://pandas.pydata.org/docs/user_guide/io.html).

## Other somewhat related articles:

JupyterHub + AWS

# Existing Content:

* [Large Datasets in Pandas](https://codesolid.com/large-data-sets-in-python-pandas-and-the-alternatives/)
* [Using SQL with Pandas](https://codesolid.com/sql-with-pandas/) (in progress)
* [How to Use the Pandas GroupBy Method](https://codesolid.com/pandas-groupby/)
* [Pandas Practice Examples](https://codesolid.com/pandas-practice-examples/)
* [How to Work With Google Sheets in Python and Pandas](https://codesolid.com/google-sheets-in-python-and-pandas/)
* [Matplotlib vs. Seaborn](https://codesolid.com/matplotlib-vs-seaborn/) (Other plotting articles -- relate to this)