## Beanstalk Setup

### Step 1:

Create a repository on beanstalk app.

### Step 2:

Clone the repo using the following command:

`` git clone https://accountname.git.beanstalkapp.com/gitreponame.git ``

### Step 3:

Add source code and the beanstalk repo as a remote repo and push the code using following commands:

`` git remote add beanstalk https://account.git.beanstalkapp.com/repo.git ``

`` git push beanstalk master ``

## Heroku Setup

### Step 1:

In the Heroku installation directory, use the following commands to prepare the app for deployment:

`` heroku login ``

`` git clone https://accountname.git.beanstalkapp.com/gitreponame.git ``

### Step 2:

In the heroku cloned directory, use the following commands to deploy the app:

`` heroku create ``

`` git push heroku master ``

`` heroku open ``