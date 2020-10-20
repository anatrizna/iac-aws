This repo include my templates for AWS CloudFormation. 

Can be modified accoring the requirements, uploaded to S3 bucket and used to create required stack in AWS. 

1. ec2-with-sg-eip.yaml - Create EC2 instance with SecurityGroup and Elastic IP
2. s3bucket-ac-name.yaml - Create S3 bucket with AccessControle
3. metadata.yaml - Shows how to use AWS::CloudFormation::Interface to group parameters displayed 
4. ec2-lamp.yaml - Create EC2 instance, SecurityGroup. Sets up EC2 instance with LAMP software stack. 
5. ec2-jenkins.yaml - Create EC2 instance, SecurityGroup. Output public IP. Set up EC2 instance with Jenkins software stack, which will be availble on port 8080. 
