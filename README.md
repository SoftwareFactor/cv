Karolis Petreikis
====

## Overview
I am a Microsoft Certified Solutions Developer specializing in technical project management, mainly in retail industry.

My technical expertise includes:

* Service-oriented architecture
* Distributed architecture
* Cloud-based solutions (Windows Azure, Amazon AWS)
* Microsoft .NET Framework and C#
* Test-driven development

More detailed list of used technologies, frameworks and practices:

**Frontend:** HTML, CSS, JavaScript, jQuery.  
**Backend:** ASP.NET MVC, Web API 2, ASP.NET Core, WCF, NServiceBus.  
**Data Access:** Dapper, Entity Framework, SQL Server, SQL Azure, PostgreSQL, Amazon RDS.  
**Cloud:** Windows Azure, Amazon AWS  
**Project Management:** Agile software development (Kanban, Scrum).  

## Education
#### ISM University of Management and Economics
**Years:** 2007 - 2011  
Bachelor of Economics studies
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
#### Programming in C# Specialist
**Years:** 2013 - present  
Microsoft, License E277-8174
#### Programming in HTML5 with JavaScript and CSS3 Specialist
**Years:** 2013 - present  
Microsoft, License E124-9423
#### Microsoft Certified Professional (MCP)
**Years:** 2013 - present  
Microsoft, License E124-9428

## Work Experience
#### Partner at Mediapark, UAB
**Years:** 2011 - present  

**Main responsibilities:**

* Leading a team of .NET developers  
* Identifying client needs  
* Estimating project cost and time-frame requirements  
* System architecture design  
* Making sure best practices are followed  
* Hands-on software development  

#### Freelance
**Years:** 2005 - 2011  

## Recent Projects

#### Warehouse management system for online retailer
**Years:** 2015 - 2017  

**My responsibilities:**

* Communication with the client
* Requirements analysis
* Architecture decisions
* Technical team leadership

**Challenges:**

* Many processes happening simultaneously had to fit into a single system: order processing, generation of orders to suppliers, unloading of incoming goods, distribution and shipping.
* Creating universal solution for integration with external systems such as web stores, route optimization solutions, accounting software, etc.

**Solution:**

* Warehouse workers scan goods using portable scanner devices (running Android OS). This allows the system to keep track of all goods in the warehouse.
* Administration area was developed using AngularJS framework.

#### Number management system for communications industry regulator
**Year:** 2015  

System provides functionality for administration of issued phone numbers. 

**My responsibilities:**

* Project management
* Requirements analysis
* Architecture decisions
* Hands-on software development

**Challenges:**

* There was a requirement to import large quantities of data from a legacy sistem.
* Some of the use cases required processing of large quantities of data in short periods of time.

**Solution:**

* SQL Server was chosen for persistence.
* Administration area was developed using AngularJS framework.

#### Virtual currency payment processing platform
**Years:** 2014 - 2015  

Online platform that allows merchants to generate invoices and get paid in virtual currencies (Bitcoin, Litecoin and Ripple).

**My responsibilities:**

* Communication with the client
* Requirements analysis
* Architecture decisions
* Technical team leadership
* Hands-on software development

**Challenges:**

* Each paid invoice starts an invisible chain of long running processes (currency conversions, hedging, transfer of funds to merchants, allocation of bonuses for affiliates, various notifications).
* We had to make sure that whole process is robust and can withstand unreliable network connections, server crashes and temporary issues with third party services.
* There was a requirement for a highly dynamic and feature rich merchant self-service area.
* Security of the system was a priority. The platform handles clients' money, so any security breach would be a disaster.

**Solution:**

* We built the system on NServiceBus messaging framework. The architecture ensures that all processes are monitored and failed operations are automatically retried. In cases where automatic recovery is not possible, administrators are notified.
* Merchant self-service area was developed from the ground up using AngularJS. It provides merchants with basic control of account as well as analytics, charts and real time notifications. All this functionality works smoothly on any device, including tablets and mobile phones.
* We thoroughly analyzed attack surface and secured the system according to the best practices, using multiple layers of security where possible.

#### Brokerage business management system
**Year:** 2014  

We built a system that automates multiple aspects of brokerage business management. It consists of self-service areas for both sales persons and clients. The system automates creation of trading accounts, automatically monitors all trading activity and calculates commissions that need to be paid to both introducing brokers and affiliates.

**My responsibilities:**

* Communication with the client
* Requirements analysis
* Architecture decisions
* Technical team leadership
* Hands-on software development

**Challenges:**

* Each new order executed by a trader starts a chain of events that result in allocation of commissions for sales persons, updating of multiple account balances, notifications being sent to third party services. A failure in any of those operations might result in client account balances being corrupted.
* There was a requirement to make introducing brokers feel like business owners. They needed to have full control over every aspect of their business.

**Solution:**

* We chose an architecture that consists of ASP.NET MVC web application and a service layer implemented using NServiceBus messaging framework. The architecture of service layer makes it possible to closely monitor critical business processes, automatically retry failed operations, or notify administrators in case of a critical fault.
* With the help of our UX specialists, we implemented a feature rich and easy to use member area for introducing brokers. They can provide their clients with individual spread and commission offerings or special bonuses.

#### Algorithmic trading platform
**Year:** 2013  

This is a distributed trading platform that consists of multiple nodes. Each node subscribes to marked data and executes custom trading logic. Orders to buy or sell securities are sent to liquidity providers via FIX protocol. Messaging architecture has been implemented using ZeroMQ queues which have a throughput in the range of 100.000s of messages per second.

Frontend of the application has been implemented using WPF and MVVM pattern.

**My responsibilities:**

* Requirements analysis
* Architecture design
* Team leadership
* Making sure best practices are followed
* Hands-on software development

## Contact Information
**Email:** karolis@mediapark.com  
**Cell phone:** +370 618 51463  
