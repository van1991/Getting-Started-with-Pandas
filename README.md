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
