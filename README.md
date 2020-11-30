# GitLab-CICD-Docker-S3-ElascticBeanstalk

This repository shows the .gitlab-ci.yml files from GitLab CI/CD for the configuration of continuous integration and continuous deployment of 2 applications:
* React with AWS S3 Static web hosting
* Spring Boot with AWS Elastic Beanstalk

Likewise, for each commit made to master, a docker image with the current date is automatically generated and registered in GitLab Registry.
