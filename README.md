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
