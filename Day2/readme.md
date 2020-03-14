# Day2 exercises assumes


To try the Day2 lab exercises, you need to install 
* Python3
* aws-cli

You may install python as shown below
	amazon-linux-extras install epel -y
	sudo yum install -y python3

You may install aws cli tool as shown below

	curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
	unzip awscliv2.zip
	sudo ./aws/install

	export PATH=$PATH:/usr/local/aws-cli/v2/2.0.3/bin

You may verify if aws-cli tool is installed correctly

	which aws
	aws --version

### You are all set now!
