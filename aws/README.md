EDIT : This version allows to create all the resources in the Terraform script with the 'owner_name' variable content appended in front of the nametags.
This makes it easier to work on the same instance of AWS and allows the partecipants to find their resources in the GUI in an easier way.

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
