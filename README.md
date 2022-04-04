# DevOps Demo Project 1
Client proposal project (proof of concept or POC) demonstrating setting  up and tearing down of entire AWS infrastructure stack using Terraform. Tools and technologies include Ansible, Terraform, Jenkins, AWS Cloud, and Docker. Project consisted of automatic provisioning of AWS cloud infrastructure, Ansible configuration management, and containerization of web application(s) using Docker.<br>

This project is now open source and can serve as a template for other projects. Feel free to clone and adapt to serve your own needs.
Showcase project featuring real-world use cases based off of actual freelance client consulting work.

This repository goes along with the [free YouTube terraform course](https://www.youtube.com/watch?v=1JAx2npuprk&list=PLtK75qxsQaMIHQOaDd0Zl_jOuu1m3vcWO)

It contains the terraform code that you can use to follow along and set up a haproxy-load-balanced group of webservers.

Have fun!


## Quickstart:

1. Clone this repo:

`git clone https://github.com/groovemonkey/digitalocean-terraform.git`

1. Set up DigitalOcean credentials:

- [DigitalOcean Signup Link](https://www.digitalocean.com/?refcode=0380a1db56a6) (if you use this link to sign up for DO, we both get some DO credits)
- [DigitalOcean SSH Key/API Token Setup video](https://www.youtube.com/watch?v=hAW6aXRHWdw&list=PLtK75qxsQaMIHQOaDd0Zl_jOuu1m3vcWO&index=2)

1. Put those credentials into the `variables.tf` file.

1. Initialize and run terraform:
```
terraform init
terraform plan
```

1. If you're ready to spend some money (or DO credits):

`terraform apply`
