# Number of Executions

In addition to Actual Rewinds and Rebinds, Number of Executions was introduced in SQL Server 2008. This value is a count of the number of times an operator was executed. For some operators, the number of executions is related to the number of rows returned, and the estimated and actual number of executions will vary in relation to the difference between the number of estimated and actual rows. In some cases, SQL Server cannot estimate the number of executions and will list a value of 1 in the Estimated Number of Executions.
