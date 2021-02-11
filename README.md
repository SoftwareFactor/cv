Karolis Petreikis
====

## Overview
I am a software solutions architect with over 10 years of hands-on development experience. My areas of specialization include:

* Domain-driven design
* Service-oriented & modular architecture
* Infrastructure as code (using Terraform) and cloud-based solutions (mostly on Amazon AWS)
* Microsoft .NET Framework and C#

A more detailed list of currently used technologies, frameworks, and practices:

**Frontend development:** HTML, CSS, JavaScript.  
**API development:** ASP.NET Core, NServiceBus.  
**Data access:** Dapper, Entity Framework, SQL Server, SQL Azure, PostgreSQL, MySQL, Amazon RDS, DynamoDB, Redis.  
**Infrastructure:** Docker, Terraform, Amazon AWS (Elastic Container Service, Lambda, CodeBuild), Microsoft Azure, CircleCI, Linux administration.  
**Other:** Domain-driven design practices, Test-driven development, Specification by example (using Gherkin testing scenarios).

## Certifications
#### Microsoft Certified Solutions Associate (MCSA): Web Applications (Charter)
**Years:** 2016 - present  
Microsoft, License F810-1225
#### Microsoft Certified Solutions Developer (MCSD): App Builder (Charter)
**Years:** 2016 - present  
Microsoft, License F810-1224
#### Microsoft Certified Solutions Developer: Web Applications (MCSD)
**Years:** 2014 - present  
Microsoft, License E930-7584
#### Microsoft Specialist: Programming in C#
**Years:** 2013 - present  
Microsoft, License E277-8174
#### Microsoft Specialist: Programming in HTML5 with JavaScript and CSS3
**Years:** 2013 - present  
Microsoft, License E124-9423
#### Microsoft Certified Professional (MCP)
**Years:** 2013 - present  
Microsoft, License E124-9428

## Formal education
#### ISM University of Management and Economics
**Years:** 2007 - 2011  
Bachelor of Economics studies

## Work experience
#### Co-founder & CTO at MindMerit, UAB
**Years:** 2020 - present  

**Main responsibilities:**

* Ownership of software development process & related optimization initiatives
* Leading of software development teams  
* Definition of technical project requirements  
* Estimation of project cost and time-frame requirements  
* Design of solution architecture  
* Hands-on software development  

#### Co-owner & partner at Mediapark, UAB
**Years:** 2011 - 2020  

**Main responsibilities:**

* Leading of software development teams  
* Definition of technical project requirements  
* Estimation of project cost and time-frame requirements  
* Design of solution architecture  
* Hands-on software development  

#### Freelance software developer
**Years:** 2005 - 2011  

## Some of my projects

#### Self-care website and mobile applications for a telecom
**Years:** 2017 - 2019  

**My responsibilities:**

* Requirements analysis
* Solution architecture
* Technical team leadership

**Challenges:**

* The client was a new telecom starting from scratch. We needed to prepare architecture for self-care app and related web services while backend systems were still in development. Some of the API documentation for backend systems was not ready and had to be anticipated in advance.
* The app needed to be scalable to handle thousands of online users at peak hours. In addition to that, the infrastructure costs had to be minimal during off-peak hours.

**Solution:**

* Our team developed an API for consumption by web and mobile self-care apps.
* API aggregated information from multiple backend telecom systems and hid all the complexity by providing a simple RESTful interface for mobile app developers to integrate with.
* We achieved scalability targets by deploying backend solution to Microsoft Azure and configuring auto-scaling of web server instances. Caching strategies were implemented using Azure Redis Cache to reduce the pressure on backend systems and self-care's SQL Azure database.

#### Electric car-sharing service with a mobile app
**Years:** 2016 - 2019  

**My responsibilities:**

* Requirements analysis
* Technical project management

**Challenges:**

* We needed to launch backend web services, admin panel, and mobile apps for two platforms on a tight schedule.
* Integrations were needed to gather data from various sources, including the fleet of vehicles and charging stations.

**Solution:**

* Our team developed an API for consumption by mobile apps.
* Integrations were made with automobile fleet control API, credit card payment providers (Braintree and Adyen), accounting software, driver license validation services, etc.

#### Warehouse management system for online retailer
**Years:** 2015 - 2017  

**My responsibilities:**

* Communication with the client
* Requirements analysis
* Solution architecture
* Technical team leadership

**Challenges:**

* Many processes happening simultaneously had to fit into a single system: order processing, generation of orders to suppliers, unloading of incoming goods, distribution and shipping.
* Creating universal solution for integration with external systems such as web stores, route optimization solutions, accounting software, etc.

**Solution:**

* We developed a mobile app for warehouse workers. The app runs on portable Android scanner devices. Workers scan barcodes at every step, and the system keeps track of all goods in the warehouse.
* We developed an administrative area using the AngularJS framework.

#### Number management system for communications industry regulator
**Year:** 2015 - 2021   

The system provides functionality for the administration of issued phone numbers.  

**My responsibilities:**

* Project management
* Requirements analysis
* Solution architecture
* Hands-on software development

**Challenges:**

* There was a requirement to import large quantities of data from a legacy system.
* Some of the use cases required processing large quantities of data in a relatively short time.

**Solution:**

* Microsoft SQL Server was chosen for persistence.
* Administration area was developed using the AngularJS framework.

#### Virtual currency payment processing platform
**Years:** 2014 - 2015  

Our team was one of the early pioneers who developed a platform that allows online merchants to transact in virtual currencies (Bitcoin, Litecoin, and Ripple).

**My responsibilities:**

* Communication with the client
* Requirements analysis
* Solution architecture
* Technical team leadership
* Hands-on software development

**Challenges:**

* Each paid invoice starts an invisible chain of long-running processes (currency conversions, hedging, transfer of funds to merchants, allocation of bonuses for affiliates, various notifications).
* We had to make sure that the whole process is robust and can withstand unreliable network connections, server crashes, and temporary issues with third party services.
* There was a requirement for a highly dynamic and feature-rich merchant self-service area.
* Security of the system was a priority. The platform handles clients' money, and any security breach would be a disaster.

**Solution:**

* We built the system on NServiceBus messaging framework. The architecture ensures that all processes are monitored, and failed operations are automatically retried. In cases where automatic recovery is not possible, administrators are notified.
* Merchant self-service area was developed from the ground up using AngularJS. It provides merchants with basic control of their accounts, including analytics, charts, and real-time notifications. All this functionality works smoothly on devices of any form factor.
* We thoroughly analyzed the attack surface and secured the system according to the best practices, using multiple security layers where possible.

#### Brokerage business management system
**Year:** 2014  

We built a system that automates multiple aspects of brokerage business management. It consists of self-service areas for both salespersons and clients. The system automates the setup of trading accounts, automatically monitors all trading activity and calculates commissions that need to be paid to both introducing brokers and affiliates.

**My responsibilities:**

* Communication with the client
* Requirements analysis
* Solution architecture
* Technical team leadership
* Hands-on software development

**Challenges:**

* Each new order executed by a trader starts a chain of events that result in allocating commissions for salespersons, updating multiple account balances, sending notifications to third party services. A failure in any of those operations could result in client account balances being corrupted.
* There was a requirement to make introducing brokers feel like business owners. They needed to have full control over every aspect of their business.

**Solution:**

* We chose an architecture that consists of ASP.NET MVC web application and a service layer implemented using NServiceBus messaging framework. The service layer's architecture makes it possible to closely monitor critical business processes, automatically retry failed operations, or notify administrators in case of a critical fault.
* With our UX specialists' help, we implemented a feature-rich and easy to use member area for introducing brokers. They can provide their clients with individual spread and commission offerings or special bonuses.

#### Algorithmic trading platform
**Year:** 2013  

This is a distributed trading platform that consists of multiple nodes. Each node subscribes to marked data and executes custom trading logic. Orders to buy or sell securities are sent to liquidity providers via FIX protocol. Messaging architecture has been implemented using ZeroMQ queues with a throughput in the range of 100.000s of messages per second.

The frontend of the application has been implemented using WPF and the MVVM pattern.

**My responsibilities:**

* Requirements analysis
* Solution architecture
* Team leadership
* Making sure best practices are followed
* Hands-on software development

## Contact Information
**Email:** karolis@meritstory.com  
**Cell phone:** +370 618 51463  
