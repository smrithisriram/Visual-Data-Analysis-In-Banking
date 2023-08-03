# Portfolio-Project-Visual-Data-Analysis-In-Banking

Python is one of the best tools for performing data analysis. It includes a wide range of modules and libraries that can perform complex operations on large datasets. Few of the modules used in this project include :

PANDAS

Pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. Here is the list of pandas functions used for analysis.

	read_csv(file_name, separator) - Load a CSV file onto a data frame. The arguments passed are the path to the  file and the separator/delimiter value.
	head(n) - Gives the first 'n' rows of the dataframe. If no argument is passed then it returns the first 5 rows by default.
 
	map(dict) - Map a set of values into another type specified by the dictionary 'dict'.
 
	columns - Returns all the columns in the dataframe.
 
	shape - Returns the shape or number of rows and columns of the dataframe as a tuple.

MATPLOTLIB

Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkit. Few plotting types used are 

	hist() - Compute and plot a histogram.
 
 	barh() - Make a horizontal bar plot.
  
  	pie() - Plot a pie chart.

SEABORN

Seaborn is a library that is built on top of Matplotlib to plot graphs. It will be used to visualize random distributions. Here are few of the more advanced plotting types provided by seaborn in addition to the matplotlib ones.

	boxplot() - A box plot shows the distribution of quantitative data in a way that facilitates comparisons between variables or across levels of a categorical variable.
 
 	histplot() - Plot univariate or bivariate histograms to show distributions of datasets.
  
  	countplot() - Show the counts of observations in each categorical bin using bars.
   
	pairplot() - Plot pairwise relationships in a dataset by creating a grid of axes such that each numeric variable in data will by shared across the y - axes across a single row and the x-axes across a single column.
 
 	heatmap() - Plot rectangular data as a color-encoded matrix.
  
  	relplot() - Figure-level interface for drawing relational plots onto a FacetGrid.
   
   	lineplot() - Draw a line plot with possibility of several semantic groupings.
 
