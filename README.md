# terraform-provisioners
## Implementing the concept of Provisioners to deploy an application on an EC2 instance. 

Terraform provisioners are used for executing scripts or shell commands on a local or remote machine as part of resource creation/deletion, and they can also transfer files from a local environment to a remote one. There are 3 available provisioners: file (used for copying), local-exec (used for local operations), remote-exec (used for remote operations). The file and remote-exec provisioners need a connection block to be able to do the remote operations.

In this project we'll create infra using Terraform and along with that we'll deploy an application on the EC2 instance and then expose this app to the external world during infrastructure creation itself.
This project also illustrates how to create a public subnet inside a VPC.
