# Karolis Petreikis
## Overview
I am a Microsoft Certified Solutions Developer specializing in software architecture planning and development. My expertise includes:

* Service-oriented architecture
* Distributed architecture
* Cloud-based solutions (Windows Azure, Amazon AWS)
* Microsoft .NET Framework and C#
* Test-driven development

More detailed list of used technologies, frameworks and practices:

**Frontend:** HTML, CSS, JavaScript, jQuery.  
**Backend:** ASP.NET MVC, Web API 2, vNext, WCF, NServiceBus, Multithreading.  
**Data Access:** Entity Framework, SQL Server, SQL Azure, PostgreSQL.  
**Cloud:** Windows Azure, Amazon AWS  
**Project Management:** Agile software development (Kanban, Scrum).  

## Education
#### ISM University of Management and Economics
**Years:** 2007 - 2011  
Bachelor of Economics studies
## Certifications
#### Microsoft Certified Solutions Developer: Web Applications (MCSD)
**Years:** 2014 - now  
Microsoft, License E930-7584
#### Programming in C# Specialist
**Years:** 2013 - now  
Microsoft, License E277-8174
#### Programming in HTML5 with JavaScript and CSS3 Specialist
**Years:** 2013 - now  
Microsoft, License E124-9423
#### Microsoft Certified Professional (MCP)
**Years:** 2013 - now  
Microsoft, License E124-9428
## Work Experience
#### Partner at Mediapark, UAB
**Years:** 2011 - 2016  

**Main responsibilities:**

* Leading a team of .NET developers  
* Identifying client needs  
* Estimating project cost and timeframe requirements  
* System architecture design  
* Making sure best practices are followed  
* Hands-on software development  

#### Freelance
**Years:** 2005 - 2011  
## Top Projects
### Project name
**Years:** 2014 - 2015  

Online platform that allows merchants to generate invoices and get paid in virtual currencies (Bitcoin, Litecoin and Ripple).

**My responsibilities:**

* Communication with the client
* Requirements analysis
* Architecture decisions
* Technical team leadership
* Hands-on software development
* Quality assurance

**Challenges:**

* Each paid invoice starts an invisible chain of long running processes (currency conversions, hedging, transfer of funds to merchants, allocation of bonuses for affiliates, various notifications).
* We had to make sure that whole process is robust and can withstand unreliable network connections, server crashes and temporary issues with third party services.
* There was a requirement for a highly dynamic and feature rich merchant self-service area.
* Security of the system was a priority. The platform handles clients' money, so any security breach would be a disaster.

**Solution:**

* We built the system on NServiceBus messaging framework. The architecture ensures that all processes are monitored and failed operations are automatically retried. In cases where automatic recovery is not possible, administrators are notified.
* Merchant self-service area was developed from the ground up using AngularJS. It provides merchants with basic control of account as well as analytics, charts and real time notifications. All this functionality works smoothly on any device, including tablets and mobile phones.
* We thoroughly analyzed attack surface and secured the system according to the best practices, using multiple layers of security where possible.

### Project name
**Year:** 2015  
Description.
### Project name
**Year:** 2015  
Description.
## Contact Information
**Email:** karolis@mediapark.lt  
**Cell phone:** +37061851463  
