the project is hosted on github at https://github.com/Shending-Help/udagram_deploy and is connected to circleci

so any new code that is added to the project will be deployed to the backend and front end through the pipeline using circleci config.yml that is in the root directory of the project

it sets the configuration needed from aws/cli and node.js and angular and all the dependencies needed and then environment variables for the backend and front end and then runs the build script in the backend and front end directories to build the project and then depoly it to the aws elastic beanstalk environment and rds database and s3 bucket

\*/
