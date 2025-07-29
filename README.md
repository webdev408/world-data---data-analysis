One of the most popular method of data analysis is importing data with pd.read_csi, or pd.read_excel or hd.read_html file. 
In this case we have read the data with pd.read_html because the data were in a table from world bank org database.
Because the data was messy with unspecified names and multi index column labels, we needed to clean that up which we
have done with rename function. The columns are renamed to make them readable and understandable. After several cleaning and 
adjusting, the data analyses proceeded with numeric analysis no plotting was attempted. In the next phase, that will come.
