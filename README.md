### pandas

```python
# merge two dataframes
df1.merge(df2, how='left', on='column_name')
```

```python
# select columns by name
df.filter(items=['one', 'three'])
```

```python
# select rows based on conditions
df[(df['username'] == 'user1019')]
```

```python
# drop columns using regex
df.drop(df.filter(regex='user').columns, axis=1)
```
