# DR Holiday Tracker.


A DR plan for a small business that generates sales receipts for different clients.


# Background

Ismi is a fairytale organization in the alps of moria that keeps tracks of holidays around the world and send messages to thier loved one. Ismi has an application called Ismi Beta that does what the business is all about which is keep track of holidays and sending messages to thier loved one. 

Ismi current application which is a .NET background service(This app just logs to file every 5 minute lol) is usually deployed manually on a VM and the VM is hosted on a physical server. But! Ismi phyical server is always raided by orcs from the land of moria which leads to data loss, customer loss and security breach.


# Goal

The Goal is to migrate Ismi to AWS and also come with a DR plan that can reduce recovery costs, ehnaced security and customer retentions.


# Migration Activity
Ismi wants to utilize the following for the new migration processs;

1. use of docker containers to increase the portability, efficiency, scalability and speed to deployments of Ismi beta.
2. Automate the creation of new infrastructure with Terraform and Github Actions
3. AWS EC2 to host their docker container 

## Objective
1. Migration must be at a very low cost and very simple architecture as Ismi is a small business
2. 

# DR activity
