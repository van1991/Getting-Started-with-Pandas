# How to subset dataframes in Python

## Focusing only on [], .loc, and .iloc

### Getting started with []

Its primary purpose is to select columns by the column names <br />
df[ ] <br />
df.loc[ ] <br />
df.iloc[ ] <br />

Select a single column as a Series by passing the column name directly to it:  <br /> df['col_name']

Select multiple columns as a DataFrame by passing a list to it:  <br />  df[['col_name1', 'col_name2']]

### Getting started with .loc
Only uses labels <br />
Can select rows and columns simultaneously <br />
Put a comma between row and column selections <br />

df.loc[row_selection, column_selection] <br />
df.loc[['Dean', 'Cornelia'], ['age', 'state', 'score']] <br />

select all rows and some columns <br />
df.loc[:, ['food', 'color']] <br />

### Getting started with .iloc

The .iloc indexer is very similar to .loc but only uses integer locations to make its selections.

Select two rows and two columns:

>>> df.iloc[[2,3], [0, 4]]

Select all the rows and a single column

>>> df.iloc[:, 5]

The above content is taken from the below link - < br />
https://medium.com/dunder-data/selecting-subsets-of-data-in-pandas-6fcd0170be9c  < br />
For more detailed information please refer to the above link
