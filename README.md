# End to End Machine Learning Project using AWS_CI_CD Pipelines

1. Main code
2. Docker Build checked
3. GitHub Workflow
4. IAM User In AWS
5. ECR Repository
6. EC2 Instance - Docker Setup
7. GitHub Action Runner
8. Repository Secrets
9. Run Continuous Integration -- Continuous Delivery -- Continuous Deployment

## Docker Setup In EC2 commands to be Executed

### Optional

sudo apt-get update -y

sudo apt-get upgrade

### Required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = ap-south-1

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = simple-app
