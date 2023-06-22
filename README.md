<img src="images/CONFIDENTDATASCIENCE.png" alt="An image that reads Confident Data Science: The Essential Skills of Data Science, Companion Jupyter Notebook + Coding Examples. Also shows book image."/>

# Confident Data Science: Discovering The Essential Skills of Data Science

A repository to provide additional references related to Confident Data Science (Nelson, 2023).

# Notebooks

If you are here in search of the companion Jupyter notebooks and coding examples look in the notebooks subfoler where you will find the following:

- [Confidend Data Chapter 5 Notebook](/notebooks/Confident%20Data%20Chapter%2005.ipynb) Data Exploration
- [Confidend Data Chapter 6 Notebook](/notebooks/Confident%20Data%20Chapter%2006.ipynb) Data Manipulation + Preparation
- [Confidend Data Chapter 8 Notebook](/notebooks/Confident%20Data%20Chapter%2008.ipynb) One Weekend Crash Course
- [Confidend Data Chapter 9 Notebook](/notebooks/Confident%20Data%20Chapter%2009.ipynb) Data (As Tool)
- [Confidend Data Chapter 10 Notebook](/notebooks/Confident%20Data%20Chapter%2010.ipynb) Data Visualization
- [Confidend Data Chapter 11 Notebook](/notebooks/Confident%20Data%20Chapter%2011.ipynb) Business Value + Clients

# Shipping + Mailing Data

If you are here looking for the data introduced in *Confident Data Science* look in the data subfolder where you will find the following files:

- [confident_ch6.csv](/data/confident_ch6.csv) - A CSV version of the shipping + mailing data shown in Chapter 6.
- [confident_ch6.html](/data/confident_ch6.html) - An HTML version of the shipping + mailing data shown in Chapter 6.
- [confident_ch6.dta](/data/confident_ch6.dta) - A Stata version of the shipping + mailing data shown in Chapter 6.

To load these data in a single line of code:

**Python + Pandas**
```Python
# Specify file location, path, and name
location = 'https://raw.githubusercontent.com/'
path = 'adamrossnelson/confident/main/data/'
name = 'confident_ch6'

# Load the csv file into a Pandas df
df = pd.read_csv(location + path + name + '.csv')
# Load the html file into a Pandas df
df = pd.read_csv(location + path + name + '.html')[0]
# Load the Stata file into a Pandas df
df = pd.read_csv(location + path + name + '.dta')
```

**R / R Studio**
```R
# Specify file location, path, and name
location <- "https://raw.githubusercontent.com/"
path <- "adamrossnelson/confident/main/data/"
name <- "confident_ch6"

# Load the CSV file into a dataframe
csv_url <- paste0(location, path, name, ".csv")
csv_data <- read.csv(csv_url)

```

# References

*Confident Data Science: Discover the essential skills of data science* <br>
(Confident Series, 15) 1st Edition by Adam Ross Nelson (Author) <br>
Publisher : Kogan Page (September 26, 2023).
