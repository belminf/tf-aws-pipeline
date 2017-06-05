# tf-aws-pipeline
Terraform AWS Pipeline

## Create stack via CLI

    aws cloudformation create-stack --stack-name tf-aws-pipeline --template-body file://cfn-template.yaml --parameters ParameterKey="RepoName",ParameterValue="tf-repo"
