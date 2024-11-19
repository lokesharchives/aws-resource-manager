# aws-resource-manager
CloudFormation Templates - GenAI

# The Repo is still under development.
The primary objective of this project is to modularize the cloudformation template and reusing them across the project. Once we achieve the modularization we will integrate genAI to manage the deployment and monitoring of the resources.

Currently we are working on modularizing the templates.

# Example

aws cloudformation package --template-file ./network/vpc/vpc.yaml --s3-bucket $BucketName --output-template-file packaged.yml
aws cloudformation deploy --template-file packaged.yml --stack-name vpc --capabilities CAPABILITY_IAM


