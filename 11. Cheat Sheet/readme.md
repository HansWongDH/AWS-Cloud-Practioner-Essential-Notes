# Cheat Sheet
## Cost explorer
	- visualize and manage AWS cost
## AWS cost and usage report
	- Detailed spreadsheet describing cost
## AWS CLI 
	- comand line interface to programmatically manage resource

## Elastic load balancer 
	- Distribute traffic between resource
## EC2 Instance type
	- Reserve, on-demand, spot, EC2 saving
## Amazon Machine Image(AMI) 
	- Template on building EC2 isntance
## AWS management console 
	- Web interace to manage aws
## AWS market place 
	- buy or sell software solution on aws
## security group 
	- stateful, control traffic at instance level (instance)
## Network Access Cotnrol List(NACL) 
	- Stateless, control traffic at network level (Subnet)
## AWS Service catalog
	- control what service can be used in an organization
## Service quiota 
	- Max Limit of something you can have or do
## Software development kit (SDK)
	- software to help integrate application language with AWS
## Support Plan
	- Basic, Developer, Business, Enterprise
## VPN
	- Secure connection between end user

# Analytic Service
## Amazon athena
	- SQL like query service to analyze logs/data
## Amazon kinesis
	- ANalyze real time streaming daata
## Amazon Quicksight
	- Dashboard and report for Business intelligent
## Application Integration

## Amazon Simple notification Service (SNS)
	- used to send notification based on event
## Amazon Simple QUeue service(SQS)
	- queue system to pass message/event between services
## Compute/Serverless

## AWS Batch
 	- Run large scale batch ML computing

## Elacstic Compute Cloud
	- Handle computing work (container)

	- General Purpose, Compute, Accelerated, Memory, Storage

## AWS Elastic Beanstalk
	- hands-off servic to deploy and scale web app

## AWS lambda
	- run serverless compute job

## Amazon Lightsail
	- like beanstalk but more hands-off

## Amazon Workspace
	- Fully managed virtual desktops

# Containers
## Elacstic Container Service (ECS)
	- Run highly secure scalabe container
## Elastic Kubernetes Service (EKS)
	- use kubernetes to manage docker container on aws
## AWS fargate
	- Deploy youra pps to AWS managed containers

# Database
## Amazon Aurora
-AWS native serverless mysql and postgresSQL service, 5x faster

## Amazon DynamoDB
	- NoSQL(non relational), single digit milisec

## Amazon ElasticCache
	- in memory caching service for speed

## Amazon RDS 
	- Relation Db services supporting popular SQL engine

## Amazon Redshift
	- Datawarehousing service

# Developer tools
## AWS codebuild
	- build and test code
## AWS codecommit
	- like github, code repo
## AWS codedeploy
	- Automated code deployment

## AWS codepipeline
	- Automated CI/CD pipeline

## Manage, Monitor, Governance

## AWS Autoscaling
	-scale up and down resources

## AWS budget
	- Set budget to control cost and be notified

## AWS cloudformation
	- use template to automate intrastructure deployment

## AWS Cloudtrail
	- Monitor user activity and api usage (who did it)

## Amazon Cloud Watch
	- Monitor the state of your AWS infrastructure (what happened in graph)

## AWS config
	- evaluate and audit the configuration and compliance of your resource (what happened in log)

## Amazon EventBridge(Cloud watch Event)
	- Trigger action based on event

## AWS license Manager
	- Manage aquired software license

## AWS Managed Service
	- AWS services where all software of the serive is maintained by AWS, help organization fully use aws

## AWS Organization 
	- Central Group and manage multiple AWS

## AWS Secret mansager
	- centrally manage lifecycle of secret (password, credentials, application credentials, OAuth tokens, API keys,)

## AWS system manager
	- Centrally monitor and configureyour resourece

	- operations hub for your AWS applications

## AWS Trust advisor
	- provide recommendation to help follow AWS best practice
	
	- Cost optimizaiton, fault tolerance, security, performance, service limit

# Networking and content delivery

## Amazon API gateway 
	- maintan and scure api

## Amazon cloudfront
	- cached data around world in edge locations to improve performance for end user

## AWS direct connect
	- ethernet cable, direct physical connection between AWS and your on-premise

	- useful for those who have high throughput workloads, so if you've got high volumes of network traffic between on-premises infrastructure and AWS Cloud, you probably do need to use AWS Direct Connect.
## Amazon Route 53 
	- DNS name resolution (give name, resolve and return ip to client)

	- time to change TTL 24 ours

## VPC
	- private area of cloud where resource deployed
# Storage
## AWS backup
	- centrally manage backup with policies

## Amazon Elastic block store(EBS)
	- block storage designed to be attached to EC2 instance

## Amaazon File System(EFS)
	- Serverless, scalable, File storage with file sharing infra

## Amazon Simple Storage Service(S3)
	- inifnitely scalable object
	
	- High read, low write

## S3 Glacier 	- Cheaper for archieve

### AWS snow Family
- physical device to move data into 
	- ### Snowcone
			14 TB
	- ### Snowball edge
			80 TB
	- ### Snowmobile
			100 PB


## AWS Storage Gateway
	- combine on premise and cloud storage

## Security, Identity, Compliance

## AWS artifact
	- download aws compliance report

## AWS certificate manager
	- create and manage SSL/TLS certificate

## AWS CloudHSM
	- physical device store encryption key, self destruct if tempered

## Amazon Cognito
	- service to provide federated identity acess service(google login etc)

## Amazon detective
	- visually analyze data for security

## Amazon GuardDuty
	- intelligent(ML) analyze and protect AWS account from malicious activity 

## IAM 
	- centrally provide and manage identity
	- least privilage
	- role specific for instance 

## Amazon Inspector
	- Inspect security status of EC2 instance

## Amazon Macie
	- ML Scan to discover,explosed sensitive data and automated protection

## AWS shield
	- protect against DDOS
	- Advanced and simple

## AWS Web app firewall
	- Protect web app from common threat

