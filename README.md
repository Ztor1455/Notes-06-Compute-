# Notes-06-Compute

## Amazon Elastic Compute Cloud or EC2

•	Provides virtual machines or instances which can host applications that usually run-on premises servers

• Gives secure & resizable compute capacity in the cloud 

•	User can launch any number of instances, of any size, and any Availability Zone

•	Using the launch instance wizard user will be given choices to configure the following

   o	**Amazon Machine Image** – template for creating EC2 Instance 

   o	**Instance Type** – determines RAM, CPU, Storage, & performance  

   o **Network Settings** – network location, public or private, VPC, & subnet

   o	**IAM Role** – if instance needs to interact, instance profile, secure credentials 

   o	**User Data** – scripts to customize the runtime, automate completion of installations and configuration at instance launch 

   o	**Storage options** – configure size of root volume, attach additional storage volumes, & specify encryption usage. 

   o	**Security groups** – set of firewall rules controlling traffic to the instance, specify source and ports that network communications can use 
   o	**Tags** – label assigned to AWS resource (key & optional value), the ability to attach metadata to an EC2 instance, filtering, automation, cost allocation, and access control 

  o	**Key pair** – specify existing or new key pair which can be either public or private 

## Cost Optimization 

•	On-Demand Instances – pay hourly, no commitment, Free tier 

•	Dedicated Hosts – physical servers with capacity dedicated for users use. 

•	Dedicated Instances – ran in a VPC dedicated to a single customer 

•	Reserved Instances – payment option for reserved instance, hourly charge discount, 1-to-3-year terms

•	Scheduled Reserved Instances -purchase capacity reservation available on recurring specified schedule & 1 year term 

•	Spot Instances – run if available, bid above spot price, can be interrupted within two-minute notification, less expensive than On-Demand instances

“Cost optimization is not a one-time process, instead you should routinely measure and analyze your systems so that you can continually improve and adjust your costs.” 

## Container Service 

“Containers are a method of operating system virtualization and are smaller than virtual machines and do not contain an entire operating system. Instead, containers share a virtualized operating system and run as resource isolated processes.”

## AWS Lambda

•	Another approach to compute that doesn’t require provision or server management.

•	Serverless computing

•	Not charged when code is not running; pay for the requests that are served and compute time 

•	No new languages, tools, or frameworks to learn 

•	Completely automates the administration, manages the infrastructure 

•	Protection against machine failures or data center failures 

## AWS Elastic Beanstalk 

•	Easy way to get web apps running 

•	Managed service that handles 

    o	Infrastructure provisioning and configuration 

    o	Deployment 

    o	Load Balancing 

    o	Automatic scaling 

    o	Health Monitoring 

    o	Analysis and debugging 

    o	Logging 

•	No additional charge

•	Fast and simple, developer productivity, difficult to outgrow, and complete resource control
