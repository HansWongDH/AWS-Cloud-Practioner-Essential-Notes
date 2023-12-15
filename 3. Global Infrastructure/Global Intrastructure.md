# AWS Global Infrastructure
## Region
- Large group of data center in a geographical location
- eg, Tokyo, Sao Paulo
### Region Specification
- Compliance to government
  - Eg, The data within US cannot get to china
- Promixity
- Feature Availability
  - new feature might not exist in certain region because lack of physical hardware
- Pricing
  - tax structure, country affect the price

## Availability zone

- Single or a group of data center within a region
- Relatively close to have low latency
- Spread out capacity to multiple availability zone to reduce downtime 

## Edge Location
- use to deliver data to region that is far away from the host

### Amazon cloudfront(CDN of amazon)

- store cached copy of data for faster delivery

### Amazon route 53 (DNS)

- help accelerate website content delivery

### Amazon Outpost

- operation mini region within customer data center with 100%  AWS functionality


## AWS Provision Management

- In AWS, everything is an api call.
### AWS Management Console
- Browser based console.
- GUI, easy to visualize and managent
- Suitable to new user
- AWS Console mobile application to perform tasks such as monitoring resources, viewing alarms, and accessing billing information. 

### AWS CLI (command line interface)
- Command line based
- Repeatable and scriptable, hence less suceptible to human error
- available in Windows, macOS, and Linux. 

### AWS Software Development kits
- AWS services through an API designed for your programming language or platform. 
- AWS services with existing applications or create entirely new applications that will run on AWS.
- Supported programming languages include C++, Java, .NET, and more

### AWS Elastic Beanstalk
- Provide Application code and configuration to build an environment
- deploy resources necessary to perform the following tasks
  - Adjust capacity
  - Load balancing
  - Automatic scaling
  - Application health monitoring

### AWS CloudFormation
- define a wide variety of AWS resources using JSON or YAML as CloudFormation templates
- Written using line of code instead of navigating through UI
- enabling frequent building of infrastructure and applications without having to perform manual actions


