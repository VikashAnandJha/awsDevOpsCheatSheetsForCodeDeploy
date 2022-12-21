sudo yum update
sudo yum install ruby
sudo yum install wget
wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install
chmod +x ./install
sudo ./install auto
sudo service codedeploy-agent start
sudo service codedeploy-agent status
sudo amazon-linux-extras install php8.0 mariadb10.5
sudo yum install -y httpd
sudo systemctl start httpd
sudo systemctl enable httpd

##points to remember
IAM : for ec2: ec2+s3+codedeploy
## userdata
edit user data
take AMI/create template
