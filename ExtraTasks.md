# Extra Tasks
For the same data set `access_log`, please find the following:

## Assignment 6

Find out how many files were hit in year 2009, year 2010, and year 2011. Determine which year had the most number of hits, and how many times it faced hits. Provide output in this format:

```
2009 X
2010 Y
2011 Z
```

## Assignment 7
Determine how many types of HTTP request methods are there with numbers. For example, "GET" is a HTTP request method. Provide output in this format:

```
GET N
...
...

```

## Assignment 8
Some file requests contain the full path, such as `http://www.the-associates.co.uk`. Sometimes, only relative path requests are made. As a result, for the same file - such as `favicon.ico` - some requests are for `http://www.the-associates.co.uk/favicon.ico`; whereas some requests are just for `favicon.ico`. Considering that all such requests are same, i.e. the domain in URL does not matter, which file was hit the most and how many times? Provide output in the following format:

```
Filename_with_relative_path N
```
