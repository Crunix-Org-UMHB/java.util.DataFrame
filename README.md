# java.util.DataFrame
This project is to create class/package that will be the java equivilent to the Python Pandas library.
More specificly it will mimic the DataFrame.

This DataFrame class accepts a ArrayList<String> type for column names and any number of List<> types for column data
  the parameters are as follows

# Parameters
DataFrame(ArrayList<String> colNames, List<>... cols)

## Instantiation example
```java
DataFrame table = new DataFrame(colNames, col1, col2, col3)
```
