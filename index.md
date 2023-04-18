---
title: CV
semantic_name: cv
layout: default
---
<img src="/img/photo.jpg" class="photo img-rounded" />

<a href="/pdf/aolshevskiy-cv.pdf" class="screen pdf-download fa-stack fa-2x">
  <i class="fas fa-file-pdf fa-stack-2x"></i>
</a>

Artyom Olshevskiy

<span class="screen">Email: [artyom.olshevskiy@gmail.com](mailto:artyom.olshevskiy@gmail.com)</span>
<span class="print">Email: artyom.olshevskiy@gmail.com</span>

<div class="clearfix"></div>

## Qualifications

* 16 solid years in enterprise software engineering
* Broad fundamental knowledge of programming technologies and platforms
* Strong tech integration skills

## Experience

### EPAM Systems

Belarus/Poland

June 2019 - Now

Lead Software Engineer

* **Epic Games Ecommerce Module**

  Technologies: Java, Spring Framework, MongoDB, AWS, DynamoDB
  
  Supporting the module that handles Fortnite purchases on supported platforms(Epic, XBL, PSN)
  
* **Epic Games Receipt Validator**

  A purchase validation microservice enabling Unreal Engine's Ecommerce functions

  Technologies: Scala, Akka, DynamoDB, Redis, AWS, Terraform
  
  Own the service. Integrated half-dozen of payment platforms in a team of 3 engineers.

* **Epic Games Friends**

  Microservice for social graph management

  Technologies: Spring Framework, MongoDB, Redis(Elasticache), AWS, Terraform
  
  Owned the service. Contributed handful of features. Coordinated successful release of three major functions.
  
* **Staffing Desk**

  Core service in EPAM ecosystem implementing company hiring and staffing processes. Covers hundreds of staffing business rules exposed as a REST webservice.

  Technologies: Spring Boot, Spring Integration, Activiti BPM, Spring XD, PostgreSQL, Kafka
  
  Contributed dozen of new features with a team of 10. Reworked an inherited notification component to reduce complexity and merge into main monorepo.

* **Certification Dashboard**
  
  POC utility project leveraging GCP managed stack.

  Technologies: Spring Boot, Spring Integration, PostgreSQL, Kafka, Google Cloud Platform, Google Pub/Sub, Google Cloud Run, Kubernetes, Terraform
  
  Implemented Coursera and Credential.net integration for data mining and realtime streaming from corporate Kafka to database over Pub/Sub.

  
### SoftServe

Ukraine

September 2016 - March 2019

Software Teamlead

* **Legals Front Office**

  A B2B front office for system mentioned above. Allows businesses to submit water counter indications to billing system for processing. It's once again Spring Boot 1.x REST backend with Angular 2 SPA frontend with some tricky integrations to billing system, SMS gate and Ukrainian state electronic signature ecosystem.
  
  Technologies: Java, SQL Server, Spring Boot, Project Lombok, AspectJ, Hibernate
  
  I was a locomotive for the project scavenging human resources here and there to get the job done :)

* **Legals Billing** 

  All in one solution using existing legacy system as functional blueprint. Has plain old school SQL Server/Spring/SOAP/JSF stack
  
  Technologies: Java, SQL Server, Elasticsearch, Spring Framework, AspectJ, Apache CXF, JSF/PrimeFaces
  
  Done code review and covered various gaps in architectual design like database schema migration, security, audit logging and performance monitoring/optimization

* **Utilities Billing**

  A transaction processing system aimed to be a core for ecosystem of municipal software. Using PostgreSQL as data storage and ElasticSearch for audit logging. Data authoring is done via classic pair of Spring Boot REST backend and Angular 2 SPA frontend. There was a plan to implement transaction processing using Spring Batch as an execution engine and Drools for business logic management, but the project was frozen before the implementation.
  
  Technologies: Java, PostgreSQL, Elasticsearch, Spring Boot, AspectJ, Hibernate 
  
  Done general technical coordination, code review and coding mission critical and tricky parts on backend. I built the fundamentals for junior staff to pick up and develop further.
  
* **Smartfridge** 

  A IOT platform for smart fridges and warehouses. We used Spark Streaming and handful of Spark batch jobs to gather and transform various info(like temperature, humidity and voltage levels) from physical devices for analysis and monitoring. Data(operational in Cassandra and warehouse in Redshift) is then published to SPA Frontend via REST services built in Play Framework.
  
  Technologies: Scala, PostgreSQL, Cassandra, AWS(Redshit, EC2, S3), Kafka, Spark, Play Framework

  Engineered everything backend. Brought MVP to full scale production requiring minimal routine maintenance.

### Klika Technologies

Belarus

November 2013 - September 2016

Software Teamlead

* **Arago AG Visual Editor** 

  Special purpose IDE for visually editing fairly complex XML entities that define automation knowledge. Built in Angular.js using Bower and Grunt to minimize boilerplate and conventionalize project management.
  
  Techonologies: JavaScript, Angular 1, Titan

  Built a dynamic plugin system where you're able to upload a package and add functionality to the system in runtime. Made Angular optimizations for rendering WYSIWYG representation for XML.

* **Data Analytics project** <span class="muted">can't mention the project's name due to NDA</span>

  A next generation business analytics engine aimed at ease of use and simplicity of UI and configuration. Consists of rich HTML5 browser app and a dozen of Java-based technologies(like Usergrid, Druid and Cassandra) integrated to provide realtime data analytics experience.
  
  Technologies: Java, MongoDB, Spring Framework, Druid, Cassandra

  Coordinated a general architectual project vision and engineered backend with deployment in a team of 5 devs and one QA

### EPAM Systems

Belarus

August 2010 - November 2013

Senior Software Engineer

* **Jive SBS customizations** 

  Jive SBS is a social network engine often used for support and social marketing.  It's a classic Spring/Struts 2/Tomcat stack with some responsive design oriented features like using Closure Templates to reuse view code in server and client side

  Technologies: Java, PostgreSQL, Spring Framework, Struts 2
  
  Worked in a team supporting and implementing support site for Adidas. I rebuilt Jive boxed forum engine to AJAX interactions instead of full page rendering.

* **Oracle RTD management interface support** 

  Oracle RTD(Real Time Decisioning) is a prediction engine. It has a container infrastructure for special artifacts that define target prediction model for different business configurations(e.g. insurance agencies or call centers)
  
  Technologies: Java, JSF/ADF
  
  Our team(3 DEVs, 2 QAs) worked directly with a stakeholder on a web interface for configuring and analyzing these deployments in ADF(a JSF-based framework form Oracle). I personally built and packaged JSF UI components and there client side UI interactions. Also reworked legacy code for app reconfiguration in runtime

* **mate1.com support** 

  Mate1.com is a pretty large dating site(said to be in world top ten dating sites) written in Struts 2 running Tomcat using Hibernate on MySQL for data storage and Kafka/ZooKeeper with Cassandra for storing realtime user activities
  
  Technologies: Java, MySQL, Kafka, ZooKeeper, Struts 2, Hibernate, GWT, Quercus
  
  Techleaded and coded with a small team(3 DEVs, 1 QA) outsourced for Canadian customer in collaboration with on site engineers

  In scope of the project our team implemented some UI-centric features, incorporated bean validation into Hibernate stack and created web service testing framework in Scala based on Dispatch and Specs

* **comedycentral.com legacy ATG Dynamo-based frontend and CMS system** 

  ATG Dynamo is a old Java EE implementation that MTV sites relied before starting PHP stack incorporation

  Technologies: Java, JavaEE 5, ATG Dynamo
  
  Maintained a comedycentral.com Dynamo instance. Coordinated almost all MTV Dynamo deployments(that eventually appeared to be based on comedycentral artifacts). I successfully coordinated migration form Sybase to MySQL
  
* **thedailyshow.com, colbertnation.com, tvland.com sites** 

  A homegrown PHP glue stack integrating various subject area datastores heavily targeted towards media content
  
  Technologies: PHP, MongoDB, Redis, MySQL
  
  colbertnation.com was rewritten using new version of inhouse PHP framework in pretty tight timeframe, customers were pleased very much

### Oxagile

Belarus

February 2007 – August 2010

Junior Software Engineer

* **Boxed online poker solution(originating from and later transferred back to Viaden Media) front and back web interfaces**  

  CodeIgniter-based using XMLRPC for interactions with standalone engine written in Java

  Technologies: PHP, MySQL, CodeIgniter
  
  We had something like ten simultaneous installs with customizations running at the same time
  
  Maintained whole PHP-based substack and most of it's Linux production deployments

* **Several niche Magento-based online stores** 

  Mostly html layouts adoption and plugin reconfiguration with some store specific backoffice functions
  
  Technologies: PHP, MySQL, Magento
  
  All stores launched and profited

* **JumpTV.com front and backoffice** 

  The system was based on old version of Drupal with some interesting optimizations(e.g. load lightweight version of Drupal stack for Ajax partials)

  Technologies: PHP, Memcached, PostgreSQL, Drupal, SOAP
  
  Our team incorporated new Web 2.0 subscription, geo targeted promotion and handful of other mission critical systems

## Education

### Belarusian State University of Informatics and Radioelectronics

2004-2010

Fields of Study: Computer Science, Computer Engineering

Degree: Specialist

<p class="muted">Specialist is a degree in Belarusian state education system between Bachelor and Master :)</p>

## Skills

### JVM stack

* Java itself
* Scala
* Kotlin
* Spring, Spring Boot
* Project Lombok
* Hibernate, JPA
* Guice for small apps
* JSF
* Everything Maven
* Gradle
* Ivy
* Ant
* JUnit, AssertJ
* Apache Spark
* Struts
* SWT
* Netty 

### Native
* Go for fun and convenience
* Basic Rust

### Databases

* PostgreSQL/Amazon RedShift
* SQL Server
* ElasticSearch
* Cassandra
* MySQL(have reasonable optimization experience)
* PL/SQL(wrote dozen of production-critical stored procedures)
* Oracle
* MongoDB

### Clouds

* Obviously Docker and Docker Compose
* Amazon Web Services
* Google Cloud Platform: Professional Cloud Architect(19 Sep 2019-2021)

### Linux/BSD

* Permanently using at home and work(running Debian Linux now)
* Distributions used a lot: Arch, Gentoo, FreeBSD

### Scripting

* Scripting my errands in Python
* Resonable knowledge of Ruby

### Frontend

* JavaScript
* Pretty good at AngularJS 1
* Typescript

### Languages

* English(B2)
* Russian(Native)

## Other

* Marital status: married

## References

<div class="screen">
Github: <a href="http://github.com/aolshevskiy">http://github.com/aolshevskiy</a>
<br />
Linkedin: <a href="http://www.linkedin.com/pub/artyom-olshevskiy/7/458/586">http://www.linkedin.com/pub/artyom-olshevskiy/7/458/586</a>
</div>
<div class="print">
Github: http://github.com/aolshevskiy
<br />
Linkedin: http://www.linkedin.com/pub/artyom-olshevskiy/7/458/586
</div>


