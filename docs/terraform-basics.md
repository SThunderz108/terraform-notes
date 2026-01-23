# Terraform Basics

## What is Terraform?
Terraform is an Infrastructure as Code (IaC) tool by HashiCorp.

Suppose you are the Devops engineer and you have been assigned the task of spinning up  a EC2 instance in AWS , Usually it takes 5mins to login to AWS Console for single EC2 instance creation, once you get a task of 100 EC2 instances then it will consume more time & margin of error will be high due to manual work.

## Why Terraform ?

Nowadays almost all cloud providers has their own set of automation tools for automating the infra. So AWS has CFT (CloudFormation Template), Azure has ARM Template, Biceps for automating the infra. So learning all this tools for each cloud isn't that easy for any devops engg.
So Terraform provides a uniform platform for provisioning the infra using Multiple providers so that devops engg don't have to worry about learning new language as such , it uses HCL [Hashi Corp Language]

Terraform supports multiple providers Like AWS, GCP , AZURE, Alibaba

## What is Provider?
Provider is nothing but plugins, plugins communicate with each cloud providers API for provisioning infra.

## Key Concepts
- Providers
- Resources
- State
- Modules

