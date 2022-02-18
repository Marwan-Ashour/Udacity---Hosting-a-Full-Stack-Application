# Hosting a Full-Stack Application

* Pipeline Status (main Branch): [![Marwan-Ashour](https://circleci.com/gh/Marwan-Ashour/Udacity---Hosting-a-Full-Stack-Application.svg?style=svg]
(https://app.circleci.com/pipelines/github/Marwan-Ashour/Udacity---Hosting-a-Full-Stack-Application/48/workflows/e6de1843-cf6a-47a1-8eff-47189326776f/jobs/57)



In this project you will learn how to take a newly developed Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers. You will use the aws console to start and configure the services the application needs such as a database to store product information and a web server allowing the site to be discovered by potential customers. You will modify your package.json scripts and replace hard coded secrets with environment variables in your code.

After the initial setup, you will learn to interact with the services you started on aws and will deploy manually the application a first time to it. As you get more familiar with the services and interact with them through a CLI, you will gradually understand all the moving parts.

You will then register for a free account on CircleCi and connect your Github account to it. Based on the manual steps used to deploy the app, you will write a config.yml file that will make the process reproducible in CircleCi. You will set up the process to be executed automatically based when code is pushed on the main Github branch.

The project will also include writing documentation covering the operations of the deployment process. Which will serve as a way to communicate with future developers and anybody involved in diagnosing outages of the Full-Stack application.

### Access Website

* Use this link: http://marwan-udagram.s3-website.us-east-2.amazonaws.com to access the website.

### Hosting

* This website is being hosted on AWS.
* Elastic Beanstalk is used for the Backend API.
* S3 bucket for the frontend and uploaded images.
* RDS database running Postgres.


![infrastructure diagram](https://user-images.githubusercontent.com/92494162/153777567-168542b9-642d-445a-887a-a6e2be42c3e3.png)

### CI/CD pipeline
* The CircleCi is linked to the project on Github.
* It is used to automatically deploy the website to the AWS.
* It is set to automatically execute once the code is being pushed into the master Github project.

![pipeline chart](https://user-images.githubusercontent.com/92494162/153777618-7a5d37fe-8d97-4ea9-9079-3dc88608d748.png)




