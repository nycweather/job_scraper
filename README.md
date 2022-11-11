# Python Job Scrapper
## Using SQLAlchemy, Pandas, Numpy and SQL to build a database in Microsoft SQL Server


### Description
-------
*This project uses python in the jupyter notebook enviroment to gather data from [Simply Hired](https://www.simplyhired.com) website. It uses the beautiful library to read in the website html. In order to have more control over the data, Pandas and Numpy is used to aggregate and normalize the data. Finally with the use of the SQLAlchemy library to pass in the Pandas dataframe to a local SQL server.*


### Initial Ideas
--------
I wanted to have a list of local jobs. Not only the job titles, but also the company, company ratings and also salary if available. I wanted to store this list of data in a SQL server due to the ease of using SQL, also the easiness SQL servers provides when it comes to connecting with data visualization applications like Tableau, PowerBI or QlikSense. So it was very important for me to use a tool such as SQLAlchemy since it makes connecting to a database no easy. 

### Couple of Issues Which Occured
--------
- Normalizing salaries using regular expressions.
- Getting the right string to connect through SQLAlchemys database engine.


### Uses For This Project
-------------
This project can be used to itentify local job trends. Also this project can be helped to identify the best job pics for you based on the position, company or salary since you are able to filter and aggregate the data with python. Also this project can be used to store job market data over time as we go towerds a recession of kinds. We can use this data to compare and contrast market outputs also add onto preexisting databases.


### Running This Project Yourself?
-------
Although this project imports the dataframe to a SQL server you can still run this script to get data from Simply Hired or other similar job boards. If you want to run this project in your machine make sure you have all the nessesary dependencies installed beforehand then simply download the script, and change the url to any website you would like to add and make sure the htlm tags are correctly. After the dataframe is populated you can perform analysis or other data science related projects.

