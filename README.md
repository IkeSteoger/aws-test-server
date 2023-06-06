# Lab 16

## Project: AWS Test Server

### Authors: Ike Steoger

### Problem Domain

Deploy a basic server to AWS Elastic Beanstalk.

### Links and Resources

- [GitHub Actions ci/cd](https://github.com/IkeSteoger/caps/actions)
- [GUI Deploy url](http://aws-test-4-env.eba-uegnz8y2.us-west-2.elasticbeanstalk.com/)
- [CLI Deploy url](http://aws-test-server2-dev.us-west-2.elasticbeanstalk.com/)

<!-- ### Collaborators

Kaeden O'maera
Josh Coffey
Reece Renninger
Ryan Gallaway -->

### Setup

#### Processes

For GUI deployment:

1. Create Environment
1. Application Name (can be same as others)
1. Environment Name (can left be default)
1. Platform - Node.js
1. Platform Branch - Node.js 18 ~ Version 5.8.2 (recommended)
1. Upload your code - give version name & local file, upload zip (including Json & server.js **DO NOT NAME INDEX.JS**)
1. Single Instance (default)
1. Exisiting Service Role: aws-elasticbeanstalk-service-role
1. EC2 instance profile: aws-elasticbeanstalk-ec2-role
1. Skip to Review, and Deploy!

For CLI deployment:

1. `eb init` in terminal
1. use default names, select a region, answer No to options
1. After making sure you **ACP** to Github, `eb create`
1. default names, select region, answer No to options
1. create auto deploys but if you make changes to code base **ACP** to Github & then `eb deploy`

### Routes

- `/` ~ Proof of life route
- `/Hello?Name=<name>` ~ Proof of life with query

<!-- #### How to initialize/run your application -->

<!-- Clone repo, `npm i`, alter `.env` file, `npm start`. -->

<!-- #### Tests

To run tests, after running `npm i`, run the command `npm test` -->

<!-- #### UML

![UML](./assets/uml.png) -->
