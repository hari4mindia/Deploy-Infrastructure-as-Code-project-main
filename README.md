
# Deploy a high-availability web app using CloudFormation


![Infrastructure Diagram](Udagram-CloudFormation-Hari.jpeg)


# Load Balancer URL: 
http://Udagra-WebAp-yfOax8uQuY4c-1708861190.us-east-1.elb.amazonaws.com

# Images-of-result have all the results from aws console

aws cloudformation update-stack --stack-name UdagramStack --template-body file://udagram.yml --parameters file://udagram-parameters.json --capabilities CAPABILITY_IAM
# Infrastructure Diagram Link
https://lucid.app/lucidchart/929a8825-8c2c-4e64-aab4-12d9058a9c36/edit?viewport_loc=-1442%2C-587%2C3700%2C1736%2C0_0&invitationId=inv_73576e0b-848a-41f7-9b3b-e23f2be22ecf



