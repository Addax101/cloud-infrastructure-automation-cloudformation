# cloud-infrastructure-automation-cloudformation
This repository contains the code and documentation for automating the provisioning and management of cloud infrastructure using AWS CloudFormation.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
* An AWS account
* AWS CLI installed and configured
* Basic knowledge of AWS services and CloudFormation
## Installing
* Clone the repository `git clone https://github.com/Addax101/cloud-infrastructure-automation-cloudformation.git`
* Change into the project's directory `cd cloud-infrastructure-automation-cloudformation`
* Run the CloudFormation template `aws cloudformation create-stack --stack-name my-stack --template-body file://template.yaml --parameters file://parameters.json`

* Use the AWS CLI to check the status of the stack `aws cloudformation describe-stacks --stack-name my-stack`
* Once the stack is created, you can use the AWS Management Console to view the resources that have been created.

## Updating the Stack
If you make changes to the CloudFormation template, you can update the stack using the following command: `aws cloudformation update-stack --stack-name my-stack --template-body file://template.yaml --parameters file://parameters.json`

## Deleting the Stack
To delete the stack and all the resources that were created, you can use the following command:
`aws cloudformation delete-stack --stack-name my-stack`
## Built With
* AWS CloudFormation - Infrastructure as Code service
* AWS CLI - Command line interface for AWS

## Authors

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
GPS
