# PredictiveModelingUsingRandSQLServerMLS
-----------------------------------------
Get started with Predictive Modeling using R and SQL Server Machine Learning Services

In 2017, Microsoft introduced SQL Server Machine Learning Services letting us run R or Python scripts in SQL Server, and providing easy access to Machine Learning on premises. 

This code sample was created to demo SQL Server MLS in the QLD SQL Server User Group meet on 1st May, 2019
https://www.meetup.com/QLD-SQL-Server-User-Group/events/260102809/

The session was focused on getting familiar with SQL Server Machine Learning Services. After going over its components and features, the host demoed building a Predictive Model using R and SQL Server Machine Learning Services.

#Demo
-----
* The demo uses the popular heart disease dataset from UCI. Using R, a predictive model is trained and tested against known results.
* After testing and comparing a few Machine Learning models, the R scripts were wrapped in SQL Server Stored Procedures letting us execute R scripts through Stored Procedures. 
* The trained models were stored in a SQL Server table, and were used to perform Machine Learning predictions through Stored Procedure calls
* Last step in the demo covered Native Scoring using the native C++ extension capabilities in SQL Server 2017

#About the Presenter
--------------------
Arjun Sivadasan

After starting his career as a .NET programmer in 2007, Arjun soon got addicted to working with data after inadvertently solving a performance problem in a team meeting. Having worn multiple hats over his career as a Database Developer, DBA and Data Team Lead, he currently leads the Data team at Minor Hotels ANZ.
Arjun is excited about innovations happening in the data space, and is focused on solving business problems through performant data solutions and fostering a culture of data-driven decision making.
