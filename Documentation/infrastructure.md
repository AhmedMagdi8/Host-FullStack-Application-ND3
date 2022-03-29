# Infrastructure Description

### DB
This App uses AWS services in order to be publicly available.
This App uses postgres db which is Relational Database and uses Aws RDS service to deploy this DB.

### API (The Backend)
This App uses Node.js runtime environment on the server side which is run, deployed and managed by Elastic Beanstalk Service
provided by AWS and Connect to the database mentioned above in order to save and retrive data

### Frontend
This app uses Angular framework on the frontend side which is deployed on AWS S3 service and fetches and retrieve data from the database
through the API back to the Users of the application.