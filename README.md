### Network Security Projects For Phising Data
# How to run this code 
os.environ["MLFLOW_TRACKING_URI"]="https://dagshub.com/Praveencse79/NetworkSecurity.mlflow"
os.environ["MLFLOW_TRACKING_USERNAME"]="Praveencse79"
os.environ["MLFLOW_TRACKING_PASSWORD"]="721322a1417c068480c604b1c1480bc5a9094320"


Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 788614365622.dkr.ecr.us-east-1.amazonaws.com/networkssecurity
ECR_REPOSITORY_NAME = networkssecurity


Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

Now testing is ready