# Pandas_practice

<h1>Welcome to my Pandas practice</h1>

<p>In this repository, I have stored all the practices that I have done in pandas including some data analysis as well.</p>

<h2>What is pandas?</h2>
<p>Pandas is a very useful library developed by Wes McKinney for munging and manipulating the data. The data structure in which pandas represents the data
is called a dataframe. It is a combination of rows or columns lets say. But more preciesly in terms of pandas, a dataframe is a collection of series. Now 
what is a series then?
</p>

<h2>What is series?</h2>
<p>A series is just like dataframe but having only one dimension. So can a dataframe be of 1D? Yes if it contains only one series.</p>

<h2>What is EDA?</h2>
<p>EDA stands for explainatory data analysis. It is a process of cleaning, manipulating, representating data in suitable format for extracting the hidden information
and patterns for decision making. In short, it is a process of making sense of any data visually and in terms of decision making.</p>

<b>Panda fundamentals</b>
<ul>
  <li>Loading dataset</li>
  <li>Indexing/Selecting</li>
  <li>Finding and dealing with Nan values</li>
</ul>

<b>Loading dataset:</b>
<p>
While practicing pandas we make our own dataframes and series but in real world we need to work with real world data. A data that we didn't created. And such data can be
very sophisticated and complex. Such dataset can be in any format like csv, excel, html and so on. And pandas have method for reading any dataset of any format into dataframe by using methods like read_csv, read_excel, read_html, read_json, read_orc, read_sas, read_spss, read_sql, read_table, and many more.
</p>

<b>Indexing/Selecting:</b>
<p>
For manipulating data, sometime we may require only some portion of data for certain operations. In order to select such portion we use methods like iloc ,loc, dataframe [["column1", "column2", ...... , "columnn"]], trauncate method etc.

<ul>
  <li>iloc is used to select certain portion of the dataframe using the row and column index (numeric ones).</li>
  <li>loc is used to select certain portion of the dataframe using the row and column labels instead.</li>
  <li>trauncate is used to select of the dataframe after defining before(previous all records from that points are deleted) and after parameter (upcoming all records from       that points are deleted) </li>
</ul>
</p>

<b>Finding and dealing with Nan values:</b>
<p>
Nan values stands for "Not a number". It occurs when some values are not in the format readable by pandas. For further analysis of data Nan values must be removed or filled. If more that half of datas are Nan values then it is better to remove it otherwise it can be filled by:
  <ul>
    <li>Simply replacing the Nan value with appropriate value</li>
    <li>forwardfill-> ffill()</li>
    <li>backwardfill-> bfill()</li>
    <li>Filling with average value (Mean)</li>
  </ul>
</p>

<div>
<h3>Types of feature: https://www.theclickreader.com/exploratory-data-analysis-with-python/</h3>
  <ul>
    <li><b>Numerical/Continuous features:</b> A feature is said to be numerical or continuous if it can take values between any two points or between the minimum or maximum values in         the features column. For example, ‘Age’ is a continuous feature.</li>
    <li><b>Categorical features:</b> A categorical feature is one that has two or more categories and each value in that feature can be categorised by them. For example, gender is a           categorical variable having two categories (male and female).</li>
    <li><b>Ordinal features:</b> An ordinal feature is similar to categorical features, but the difference between them is that we can have relative ordering or sorting between the           values. For eg: If we have a feature like Height with values Tall, Medium, Short, then Height is an ordinal variable.</li>
    <li><b>DateTime features:</b> A feature is said to be a DateTime feature if the feature holds DateTime values. For example, a feature with the value ‘2020/02/01 01:01:00″ is a             DateTime feature. </li>
    <li><b>Co-ordinate features:</b> A feature is said to be a co-ordinate feature if the feature holds co-ordinate values. For example, a feature with the value ‘(27.7172,                    85.3240)’ is a co-ordinate feature. </li>
    <li><b>Frequency features:</b> A feature is said to be a frequency feature if the feature holds a count of items as its value.</li>
  </ul> 
</div>
