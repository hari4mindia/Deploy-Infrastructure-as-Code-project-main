
# Deploy a high-availability web app using CloudFormation


![Infrastructure Diagram](Udagram-CloudFormation-Hari.jpeg)


# Load Balancer URL: 
http://Udagra-WebAp-hTXhBwf0tP6z-1699872487.us-east-1.elb.amazonaws.com


# Deployment Instruction output

C:\Users\Hari\Desktop\H_Ws\Deploy-Infrastructure-as-Code-project-main\starter>aws cloudformation create-stack --stack-name UdacityUdagramStack --template-body file://network.yml --parameters file://network-parameters.json --capabilities CAPABILITY_IAM
{
    "StackId": "arn:aws:cloudformation:us-east-1:405341837454:stack/UdacityUdagramStack/eea91460-4369-11ef-b9fe-0affcb0d4571"
}


C:\Users\Hari\Desktop\H_Ws\Deploy-Infrastructure-as-Code-project-main\starter>aws cloudformation create-stack --stack-name UdagramStack --template-body file://udagram.yml --parameters file://udagram-parameters.json --capabilities CAPABILITY_IAM
{
    "StackId": "arn:aws:cloudformation:us-east-1:405341837454:stack/UdagramStack/26eaf8f0-4376-11ef-9a41-1272aeae96df"
}

# Images-of-result have all the results from aws console

aws cloudformation update-stack --stack-name UdagramStack --template-body file://udagram.yml --parameters file://udagram-parameters.json --capabilities CAPABILITY_IAM
# Infrastructure Diagram Link
https://lucid.app/lucidchart/929a8825-8c2c-4e64-aab4-12d9058a9c36/edit?viewport_loc=-1442%2C-587%2C3700%2C1736%2C0_0&invitationId=inv_73576e0b-848a-41f7-9b3b-e23f2be22ecf



