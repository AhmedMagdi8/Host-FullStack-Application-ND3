### Pipeline Description
This App uses CircleCi services to Configure a Pipeline for the application.
whenever a commit is made to the master branch on the github repo, a notification will trigered to the pipeline
to build, test and deploy the application

### pipeline steps

Spin up environment

Preparing environment variables

Checkout code

Install NodeJS 14.15.3

Install NPM

node --version

Checkout code

Install AWS CLI v2

Disable AWS pager if not already configured

Configure AWS Access Key ID

Configure AWS Secret Access Key

Configure AWS default region

Setting Up Elastic Beanstalk CLI

Front-End Install

Back-End Install

Front-End Build

Back-End Build

Back-End deploy

Front-End deploy