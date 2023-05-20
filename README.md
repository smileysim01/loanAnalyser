# loanAnalyser

In this project, we've used Spark to analyze loan applications in WI. We loaded our data to Hive tables and views so we could easily query them. The big table (loans) has many IDs in columns; we joined these against other tables/views to determine the meaning of these IDs. In addition to our analysis, we studied the performance impact of caching and bucketing.

Learning objectives:

load data to Hive tables and views;

write queries that use filtering, joining, grouping, and windowing;

interpret Spark query explanations;

optimize queries with bucketing and caching
