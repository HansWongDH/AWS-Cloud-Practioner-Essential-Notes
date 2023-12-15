# Migration and Innovation

## AWS Cloud Adoption Framework (AWS CAF)
- Each Perspective is used to uncover gaps in your skills and processes, which are then recorded as inputs use to create **AWS Cloud Adoption Framework Action Plan**
- 
### Business Perspective(strategy and outcomes)
- Strategy management
  - Leverage cloud to accelerate your business outcomes
- Portfolio management
  -  Prioritize cloud products and initiatives in line with strategic intent, operational efficiency, and your capacity to deliver.
- Business insights
  - Gain real-time insights and answer questions about your business. 
- Data monetization
  Leverage data to obtain measurable business benefit.
- Innovation management
  - Leverage cloud to develop new, and improve existing, processes, products, and experiences
- Product management
  - Manage data- and cloud-enabled offerings that deliver repeatable value to internal and external customers as products through their lifecycles

### People perspective(culture and change)
- Culture evolution
  -  Evaluate, incrementally evolve, and codify organizational culture with digital transformation aspirations, and best practices for agility, autonomy, clarity, and scalability
- Transformational leadership
  - Strengthen your leadership capability and mobilize leaders to drive transformational change and enable outcome-focused, cross-functional decision making
- Cloud fluency
  - developing a deep understanding and proficiency in digital technologies to confidently and effectively leverage cloud to accelerate business outcomes. 
- Workforce transformation
  - Train and identify a digitally fluent high-performing and adaptable workforce that can autonomously drive key capabilities. 
- Organization design
  - Assess organization design for alignment with the new cloud ways of working
- Change acceleration
  -Accelerate adoption to the new ways of working by applying a programmatic change acceleration framework that identifies and minimizes impacts to people
- Organizational alignment
  - Establish ongoing partnership between organizational structures, business operations, processes, talent, and culture to enable enterprise rapid adaptation to market conditions, and the ability to capitalize on new opportunities
### Governance Perspective(control and oversight)
- Program and project management
  - Deliver interdependent cloud initiatives in a flexible and coordinated manner.
- Benefits management 
  - Ensure that the business benefits associated with your cloud investments are realized and sustained
- Risk management
  - Leverage cloud to lower your risk profile
- Cloud financial management 
  -  Plan, measure, and optimize your cloud spend. Combine the ease of resource provisioning and agility benefits provided by cloud with financial accountability
- Application portfolio management
  - Manage and optimize your application portfolio in support of your business strategy.
- Data governance
  - processes and analytics capabilities depend on accurate, complete, timely, and relevant data.
- Data curation
  -  Collect, organize, access, and enrich metadata and use it to organize an inventory of data products in a Data Catalog. 
### Platform Perspective(infrastructure and applications)
- Platform architecture
	- Establish and maintain guidelines, principles, patterns, and guardrails for your cloud environment.
- Data architecture
	- Design and evolve a fit-for-purpose data and analytics architecture. 
- Platform engineering 
	- Build a compliant multi-account cloud environment with enhanced security features, and packaged, reusable cloud products.
- Data engineering 
	- Automate and orchestrate data flows across your organization.
- Modern application development
	- Build well-architected cloud-native applications.
- Provisioning and orchestration
	- create, manage, and distribute catalogs of approved cloud products to end users.
- Continuous integration and continuous delivery(CI/CD)
	- Evolve and improve applications and services at a faster pace than organizations using traditional software development and infrastructure management processes.

### Security Perspective(compliance and assurance)
- Security governance
  - Develop, maintain, and effectively communicate security roles, responsibilities, accountabilities, policies, processes, and procedures. 
- Security assurance
  - Continuously monitor, evaluate, manage, and improve the effectiveness of your security and privacy programs. 
- Identity and access management
  -  Manage identities and permissions at scale
- Threat detection 
  - Understand and identify potential security misconfigurations, threats, or unexpected behaviors
- Vulnerability management
  - Continuously identify, classify, remediate, and mitigate security vulnerabilities.
- Infrastructure protection
  - Validate that systems and services within your workload are protected against unintended and unauthorized access and potential vulnerabilities.
- Data protection
  - Maintain visibility and control over data, and how it is accessed and used in your organization.
- Application security
  - Detect and address security vulnerabilities during the software development process.
- Incident response
  - Reduce potential harm by effectively responding to security incidents. 
### Operations Perspective(health and availability)
- Observability
  -  Gain actionable insights from your infrastructure and application data. When you are operating at cloud speed and scale,
- Event management (AIOps)
  - Detect events, assess their potential impact, and determine the appropriate control action
- Incident and problem management 
  - Quickly restore service operations and minimize adverse business impact
- Change and release management
  - Introduce and modify workloads while minimizing the risk to production environments.
- Performance and capacity management 
  - Monitor workload performance and ensure that capacity meets current and future demands
- Configuration management 
  -  Maintain an accurate and complete record of all your cloud workloads, their relationships, and configuration changes over time
- Patch management 
  - Systematically distribute and apply software updates.
- Availability and continuity management
  - Ensure availability of business-critical information, applications, and services.
- Application management 
  - investigate and remediate application issues in a single pane of glass.

## Migration Strategy (6 Rs)
### Rehost
 - This strategy is also known as **lift and shift**
 - Using this strategy, you move your applications from your source environment to the AWS Cloud without making any changes to the application.

 ### Replatforming
 - This strategy is also known as **lift, tinker, and shift** or **lift and reshape**.
 - Using this migration strategy, you move the application to the cloud, and you **introduce some level of optimization without changing the core code** in order to operate the application efficiently, to reduce costs, or to take advantage of cloud capabilities. 

### Refactor or re-architect
- modify code architecture by taking full advantage of cloud-native features to improve agility, performance, and scalability.
- driven by strong business demand to scale, accelerate product and feature releases, and to reduce costs.

### Retire
- This is the migration strategy for the applications that you want to decommission or archive.
- There is no business value in retaining the application or moving it to cloud and eliminate the cost of maintaining and hosting the application.
- reduce the security risks of operating an application that uses an operating system (OS) version or components that are no longer supported.

### Retain
- This is the migration strategy for applications that you want to keep in your source environment or applications that you are **not ready to migrate.** 
- Security and compliance - retain applications in order to remain in compliance with data residency requirements
- High risk - requires a detailed assessment and plan prior to migration.
- Dependencies - retain an application if you need to migrate one or more other applications first.
- Unresolved physical dependencies -  dependent on specialized hardware that does not have a cloud equivalent, such as machines in a manufacturing plant.

### Repurchase
- This strategy is also known as **drop and shop**.
- You replace your application with a different version or product.
- Moving from a traditional license to SaaS 
- Version upgrades or third-party equivalents
- Replacing a custom application 