# Installing the CodeDeploy agent on EC2
sudo yum update -y
sudo yum install -y ruby wget
wget https://aws-codedeploy-eu-west-1.s3.eu-west-1.amazonaws.com/latest/install
chmod +x ./install
sudo ./install auto
sudo service codedeploy-agent status



deploy
staging

ada huil dan testing tapi vitur


staging ke prod stres test



sudo amazon-linux-extras install epel -y
sudo yum install stress -y

https://arstech.net/install-stress-on-amazon-linux/