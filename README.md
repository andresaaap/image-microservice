# Full Stack Apps on AWS Project

You will be developing a NodeJS server and deploying it on AWS Elastic Beanstalk. 
You will build upon the application we've developed during the lessons in this course. You'll complete a REST API endpoint in a backend service that processes incoming image URLs.

## Getting Started

## Project Instructions

1. [Create a config.yml for deploying the .zip](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-configuration.html#eb-cli3-artifact)
2. [Install zip](https://www.thegeekdiary.com/zip-command-not-found/)
3. [Configure the EB CLI](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-configuration.html)
4. [Eb create](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-getting-started.html#ebcli3-basics-create)

## Testing

Successful URL responses should have a 200 code. Ensure that you include error codes for the scenario that someone uploads something other than an image and for other common errors.

## Endpoint URL for the running elastic beanstalk deployment
http://image-project-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://test-s3-medi.s3.us-east-2.amazonaws.com/542.png

## FAQ
ERROR: Application Version does not exist locally
Use the complete path to the artifact
Try running eb create in the .elasticbeanstalk

## License

[License](LICENSE.txt)
