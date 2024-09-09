# Chest_Disease_Classification_CT_scan_using_MLOPS

conda activate cnn

pip install -r requirements.txt

# AWS Deployment
ECR Repos: 250738637992.dkr.ecr.us-east-1.amazonaws.com/chestxrayclassification

### steps

> sudo apt-get update -y

> sudo apt-get upgrade

> sudo apt install docker.io

> sudo sh get-docker.sh

> sudo usermod -aG docker ubuntu

> newgrp docker


### Add the secrets

AWS_ACCESS_KEY_ID = 

AWS_SECRET_ACCESS_KEY =

AWS_REGION=

AWS_ECR_LOGIN_URI=

ECR_REPOSITORY_NAME=