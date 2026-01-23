# Terraform Basics

## What is Terraform?
Terraform is an Infrastructure as Code (IaC) tool by HashiCorp.

Suppose you are the Devops engineer of your organization and you have been assigned the task of spinning up  a EC2 instance in AWS , Usually it takes 5mins to login to AWS Console for single EC2 instance creation, once you get a task of 100 EC2 instances then it will consume more time & margin of error will be high due to manual work.

## Why Terraform ?

1. **MultiCloud support** : Nowadays almost all cloud providers has their own set of automation tools for automating the infra. So AWS has CFT (CloudFormation Template), Azure has ARM     Template, Biceps for automating the infra. So learning all this tools for each cloud isn't that easy for any devops engg.
So Terraform provides a uniform platform for provisioning the infra using Multiple providers so that devops engg don't have to worry about learning new language as such , it uses HCL [Hashi Corp Language]

 Terraform supports multiple providers Like AWS, GCP , AZURE, Alibaba

2. **Large EcoSystem** : Terraform has a vast ecosystem of providers and modules contributed by both HashiCorp and the community.
3. **Declarative Syntax** : It uses declarative syntax which means allowing you to specify desired end state for your infrastructe and also it makes easier to understand  code.
4. **State Management** : State file used to identify the current state of your infrastructure.
5. **Plan & Apply** : Terraform plan helps to review what changes it gonna make so that we can rectify unexpected changes. Terraform apply will apply changes in your infrastructure.
6. **Community Support** : It has large community active user support which helps you to troubleshoot issues & get documentation help as well.
7. **HCL** : HCL stands for HashiCorp Language which is much easier for enduser to understand & define the infrastructure.

## What is Provider?
Provider is nothing but plugins, plugins communicate with each cloud providers API for provisioning infra.

## Key Concepts
- Providers
- Resources
- State
- Modules

