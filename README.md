# Cloud Server

## [Simple Server Deployed via EB GUI](http://basicserver-env.eba-rfnb6qc8.us-east-2.elasticbeanstalk.com/)

Step 1. Login to AWS
Step 2. Go to Elastic Beanstalk and "Create New Application"
Step 3. Go through configuration and upload zip file containing the app
Step 4. After the app uploads, you can run it from the link provided

## [Simple Server Deployed via EB CLI](http://eb-server-env.eba-5sckxcsm.us-west-2.elasticbeanstalk.com/)

**Note I have added Github Actions EB deploy to this repo**

Step 1. Setup app and github repo
Step 2. From terminal ```eb init``` and go through configs (and do NOT setup CodeCommit !!!!)
Step 3. ```eb create environment-name```
Step 4. Console will log progress and will provide you the link to the app when it is deployed  
Step 5. Added Beanstalk Deploy to my github repo actions
Step 6. Entered secret variables to the github repo
Step 7. ``eb deploy``` and watch that deploy the changes I committed to the master branch
