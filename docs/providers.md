Providers are nothing but plugins used by Terraform to communicate with third-party API for defining the infrastructure
So Terraform connects to multiple cloud providers using API as a code.

In Terraform configuration file demo.tf you can use multiple providers in the same config file

Example : Demo.tf

resource local_file "fruits" {
   filename = "/root/fruits.txt"
   content = "Mango is the king of fruits"
}

resource "aws_instance" "webservers" {
  ami           = "ami-0c2f25c1f622021ff4d"
  instance_type = "t2.large"
}



Here in the above example 2 Providers has been define 1st is **Local** , 2nd is the **AWS** provider

Here Two resource has been defined in the demo.tf

**resource local_file "fruits"**
resource : It's the resource block defined.
local_file : It has 2 parts , Here **local** is the provider after underscore (_) **file** its the **resource type**.
fruits : It's the resource name which we define, it can be anything.


**resource "aws_instance" "webservers"**
resource : It's the resource block defined.
aws_instance : It has 2 parts , Here **AWS** is the provider after underscore (_) **instance** its the **resource type**.

