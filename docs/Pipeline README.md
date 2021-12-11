# Pipeline Process

1. Environment varibale are prepped out

2.CircleCi installs NPM and checks out the code. 

3. CircleCi installs AWS CLI 

4. CircleCi has all of the needed enviropment variables listed in it.  CircleCi will then give these variables to the Elasticbeanstalk environment. 

5. CircleCi run scripts to install the front and back end of the application.

6. CircleCi runs scripts to build the front-end 1st then the backend of the application. 

7. Finally CircleCi will run scripts to depoly first the front-end of the application followed by the backend. 


## Please see the CircleCi Pipeline.jpg image to gain a bettwe understaning of the above steps. 


