# Infrastructure of the project

-This application runs on AWS

## Front-end

-The front-end of the application is hosted on and AWS S3 bucket.  
-This bucket fetches data from the api which is on AWS elasticbeanstalk
-This bucket also communicates authentication tasks.

## Backend
-Two parts
    -API
    -Database
-The API is hosted on AWS elasticbeanstalk. 
-The database is hosted on AWS RDS
-The front-end fetches data from the API which in turn saves data to the database. 

### Please look at the document AWS Overview.jpg for a diagram map of the above system.