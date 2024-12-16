EDIT : This version allows to create all the resources with the owner_name tag appended, so that it's possible for multiple users to use the script on the same account.

Simple example for creating a VPC in AWS

Usage:

Set up your AWS access in your local environment, so that the command

        aws sts get-caller-identity

Gives you a positive response.

Set up terraform.tfvars to your liking, then run the usual

        terraform init
        terraform plan
        terraform apply

Good luck!
