This project explains how to create a Linux EC2 instance on AWS using Terraform. It helps you set up a cloud server easily by writing simple code instead of doing everything manually on the AWS console. The main goal of this project is to show how Terraform can make the process of creating and managing cloud resources faster and more consistent.

The tools used in this project include Terraform, which helps in building and managing cloud resources using code, and AWS EC2, which provides a virtual Linux server to run your applications. AWS IAM is used to give Terraform permission to access and create resources on AWS. Git and GitHub are used to store and track project files, and the commands are run using either a Windows or Ubuntu terminal.

In this project, Terraform is used to automatically create a Linux EC2 instance on AWS along with its security settings. This means you do not need to manually create servers or configure security groups from the AWS website. Instead, a few Terraform commands can do everything for you.

The project performs a few main tasks. It launches a Linux EC2 instance, sets up a security group for safe access, and uses or creates a key pair for SSH login. The whole process is automated, making it simple and time-saving.

The project is made up of a few important files. The main file, called main.tf, contains the code to create the EC2 instance and security group. The terraform.lock.hcl file keeps track of the provider details used by Terraform, and the README.md file includes all the project information and usage instructions.

DevOps Engineer -----> Terraform files -----> Terraform Core -----> AWS , Azure
                            (.tf)                   |
                                                    |
                                                    |
                                                    |
                                                    |
                                                    -
                                             Terraform State
                                               (.tfstate)