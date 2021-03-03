# java.util.DataFrame
This project is to create class/package that will be the java equivilent to the Python Pandas library.
More specificly it will mimic the DataFrame.

This DataFrame class accepts a ArrayList<String> type for column names and any number of List<> types for column data
  the parameters are as follows

# Parameters
DataFrame(ArrayList<String> colNames, List<>... cols)
* ArrayList<String> colNames (optional)
** An ArrayList of type String that contains the column names of the table.
** The length (size()) of the ArrayList must be equal to the number of data columns
* List<>... cols,
** Any number of List<> Objects of any type that contain one column of data

## Instantiation example
```java
DataFrame table = new DataFrame(colNames, col1, col2, col3)
```
