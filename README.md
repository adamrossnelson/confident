# The Companion Repository: 

<img src="images/CONFIDENTDATASCIENCE.png" alt="An image that reads Confident Data Science: The Essential Skills of Data Science, Companion Jupyter Notebook + Coding Examples. Also shows book image."/>

Hello, I'm thrilled to welcome you to this companion GitHub repository for my book, *Confident Data Science: Discover the Essential Skills of Data Science* [Book available on Amazon.com](https://a.co/d/6lUNwp5).

With this book and repository, I'm offering a unique opportunity to explore the world of data science. Raw data is just the beginning; it is in its interpretation, analysis, and the innovations we derive from our data that provide the potential for value. In the present working world the role of data science is becoming indispensable.

A premise of this book is that anyone can "do data science" With the help of this book, can leave a significant mark on your organization, with data science.

### This Book is for You

In *Confident Data Science*, I share key insights and practical tools to help you build your confidence in this ever-evolving field. Whether you're a beginner who's just stepping into this world or an intermediate or advanced practitioner seeking to sharpen your skills, this book has something for you.

I created this repository to accompany the book. At a minimum this repository provides access to the code I wrote about and explained in the book. This repository also provides access to the data I reference in the book.

By engaging with this repository, I hope you will feel more connected with the material, find inspiration, and gain practical experience that will serve you in your data science journey. Remember, the key to mastery is practice, and this platform provides an environment for that.

Happy learning!

# Notebooks

If you are here in search of the companion Jupyter notebooks and coding examples look in the notebooks subfoler where you will find the following:

- [Chapter 5 Notebook](/notebooks/Confident%20Data%20Chapter%2005.ipynb) Data Exploration
- [Chapter 6 Notebook](/notebooks/Confident%20Data%20Chapter%2006.ipynb) Data Manipulation + Preparation
- [Chapter 8 Notebook](/notebooks/Confident%20Data%20Chapter%2008.ipynb) One Weekend Crash Course (Sentiment Analysis)
- [Chapter 9 Notebook](/notebooks/Confident%20Data%20Chapter%2009.ipynb) Data (As a Tool)
- [Chapter 10 Notebook](/notebooks/Confident%20Data%20Chapter%2010.ipynb) Data Visualization
- [Chapter 11 Notebook](/notebooks/Confident%20Data%20Chapter%2011.ipynb) Business Value + Clients (Predictive Models)
- [Appendicies Notebook](/notebooks/Confident%20Data%20Appendicies.ipynb) Notebooks + Coding Quick Start Tutorials

# Example Data

When you are looking for example data for training, testing, or demonstration purposes you can use the data found here as a general repository. With proper attribution to the book, I encourage others to use these data when building their own examples, conducting their own tests, or building their own demonstrations.

## Shipping + Mailing Data

If you are here looking for the data introduced in *Confident Data Science* look in the data subfolder where you will find the following data sets (periodically updated):

- **Fictional package shipping data.**
- **Part fictional, part actual LinkedIn data.**

## A Primer on Loading The Data

### The name conventions

The data from Chapter 6 well exemplify the conventions for naming these files. I provide the data in multiple formats including CSV, HTML, and Stata.

- [confident_ch6.csv](/data/confident_ch6.csv) - A CSV version of the shipping + mailing data shown in Chapter 6.
- [confident_ch6.html](/data/confident_ch6.html) - An HTML version of the shipping + mailing data shown in Chapter 6.
- [confident_ch6.dta](/data/confident_ch6.dta) - A Stata version of the shipping + mailing data shown in Chapter 6.

### Loading these data with code

Of course you are welcome to download the files directly through your web browser from this repository. However it may be more efficient to load these data from online in your code. Again working with Chapter 6 data here are examples of how to accomplish this.

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

# Suggested Reference Formats

**APA Reference List Style**

Nelson, A. R. (2023). *Confident data science: Discover the essential skills of data science* (1st ed.). Kogan Page.

**Chicago Reference List Style**

Nelson, Adam Ross. 2023. *Confident Data Science: Discover the Essential Skills of Data Science.* 1st ed. London: Kogan Page.

**Chicago Footnote Style**

Adam Ross Nelson, *Confident Data Science: Discover the Essential Skills of Data Science.* (2023)

**Associated Press Reference List Style**

Nelson, A. R. (2023). "Confident Data Science: Discover the Essential Skills of Data Science." Kogan Page.

**MLA Reference List Style**

Nelson, Adam Ross. Confident Data Science: Discover the Essential Skills of Data Science. 1st ed., Kogan Page, 2023.

