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

* 19 solid years in enterprise software engineering
* Broad fundamental knowledge of programming technologies and platforms
* Strong tech integration skills

## Experience

### EPAM Systems — Lead Software Engineer

Belarus/Poland · June 2019 – April 2026

* **Epic Online Services Receipt Validator Rework** *(Aug 2024 – Apr 2026)*

  Owned the migration of the purchase validation microservice for Unreal Engine Ecommerce from Scala/Akka to Java/Spring Boot, triggered by Lightbend's licensing change. Core logic and infrastructure were complete at handover; the engagement ended before production release due to Epic's workforce reduction.

  <span class="muted">Stack:</span> Java, Spring/Spring Boot, Spring WebFlux, DynamoDB, Redis, AWS, Terraform, Kargo/Argo, Helm

* **Epic Games Ecommerce Module** *(Apr 2023 – Aug 2024)*

  The ecommerce backend module powering Fortnite real-money purchases across Epic, XBL, PSN, and Switch. Designed and implemented chargeback/refund flows for Microsoft and PlayStation platforms; supported subscription-based purchase integrations. Also built SQS archival and recovery utilities (Lambda function with multi-threaded pipeline to S3, CLI restore tool with date-range filtering).

  <span class="muted">Stack:</span> Java, Spring Framework, MongoDB, AWS (SQS, S3, Lambda)

* **Epic Online Services Receipt Validator** *(Jan 2021 – Apr 2023)*

  Built the purchase validation microservice for Unreal Engine Ecommerce from scratch and released it within the first year. Owned the service end-to-end in a team of three engineers; integrated with twelve-plus platform storefronts (EGS, XBL, PSN, Steam, Nintendo Switch, iOS, Android, Amazon, Samsung, Meta Quest, Pico, and others) to validate receipts and redeem purchased products in-game.

  <span class="muted">Stack:</span> Scala, Akka, DynamoDB, Redis, AWS, Terraform

* **Epic Games Friends** *(Apr 2020 – Dec 2020)*

  A performance-critical social graph microservice managing Fortnite friend lists, with a large MongoDB store tuned for a handful of high-throughput operations. Owned the service and shipped three major feature releases.

  <span class="muted">Stack:</span> Spring Framework, MongoDB, Redis, AWS, Terraform

* **Staffing Desk** *(Oct 2019 – Apr 2020)*

  Core EPAM staffing platform exposing hundreds of business rules as a REST API, with Activiti BPM driving position workflow. Contributed a dozen features in a team of ten, including a Kafka integration with opportunities.epam.com; refactored an inherited notification component; and established a Spring Integration testing framework adopted across the team.

  <span class="muted">Stack:</span> Spring Boot, Spring Integration, Activiti BPM, Spring XD, PostgreSQL, Kafka

* **Certification Dashboard** *(Jun 2019 – Sep 2019)*

  A POC that pulled EPAM employee certification data from Coursera and Credential.net and streamed it into a GCP-managed database. Implemented both integrations and the end-to-end Kafka → Pub/Sub pipeline.

  <span class="muted">Stack:</span> Spring Boot, Spring Integration, PostgreSQL, Kafka, Google Cloud Platform, Google Pub/Sub, Google Cloud Run, Kubernetes, Terraform

### SoftServe — Lead Software Engineer

Ukraine · September 2016 – March 2019

* **Legals Front Office** *(Sep 2018 – Mar 2019)*

  A B2B portal for submitting water utility counter readings and processing batch SMS billing notifications, with integration into the Ukrainian state digital certificate system for document signing. Built deliberately isolated from the chaotic legacy backend — querying SQL directly and calling the SOAP backend only when unavoidable. Drove delivery with two frontend engineers.

  <span class="muted">Stack:</span> Java, SQL Server, Spring Boot, Project Lombok, AspectJ, Hibernate

* **Legals Billing** *(Apr 2018 – Sep 2018)*

  Legacy billing system for a state water utility — a Spring/SOAP/JSF stack with business logic scattered arbitrarily across layers. Covered code review, schema migration, security, audit logging, and performance work.

  <span class="muted">Stack:</span> Java, SQL Server, Elasticsearch, Spring Framework, AspectJ, Apache CXF, JSF/PrimeFaces

  *(Nov 2017 – Apr 2018)* Also led early stages of a greenfield municipal billing rewrite before the project was frozen.

* **Smartfridge** *(Sep 2016 – Nov 2017)*

  An IoT platform for Nestle cold storage fridges and warehouses — sensor readings streamed via Kafka through Spark Streaming to Redshift and a Play Framework dashboard. Stepped up as lead after the original teamlead departed and brought the backend to production. Contributed core streaming logic: sensor state enrichment, door handling, geolocation processing, and warehouse schema/ETL.

  <span class="muted">Stack:</span> Scala, Spark, Spark Streaming, Kafka, PostgreSQL, Cassandra, AWS (Redshift, EC2, S3), Play Framework, Docker

### Klika Technologies — Lead Software Engineer

Belarus · November 2013 – September 2016

* **Arago AG Visual Editor** *(Mar 2015 – Sep 2016)*

  A special-purpose IDE for visually editing XML-based automation knowledge — an SVG node graph with Angular-driven sidebars and CodeMirror syntax highlighting. Migrated the module system to Browserify with dynamic plugin loading; identified and fixed an Angular rendering bottleneck that caused an instant performance gain.

  <span class="muted">Stack:</span> JavaScript, Angular 1, Browserify, CodeMirror

* **Data Analytics project** *(Nov 2013 – Mar 2015)* <span class="muted">(name withheld, NDA)</span>

  A next-generation business analytics engine: rich HTML5 app over a Java backend integrating Usergrid, Druid, and Cassandra for real-time analytics. Architected the backend and coordinated project vision in a team of five engineers and one QA.

  <span class="muted">Stack:</span> Java, MongoDB, Spring Framework, Druid, Cassandra

### EPAM Systems — Senior Software Engineer

Belarus · August 2010 – November 2013

Early career work on Adidas social platform (Jive SBS), Oracle RTD management UI, mate1.com, and MTV/Comedy Central legacy systems. <span class="muted">Stack:</span> Java, Spring, JSF, PHP.

### Oxagile — Junior Software Engineer

Belarus · February 2007 – August 2010

PHP full-stack across JumpTV (Drupal), Viaden online poker (CodeIgniter), and Magento stores.

## Education

### Belarusian State University of Informatics and Radioelectronics

2004 — 2010

Fields of Study: Computer Science, Computer Engineering

Degree: Specialist

<p class="muted">Specialist is a 5-year integrated degree in the Belarusian system, positioned between Bachelor and Master.</p>

## Skills

### JVM

* Java, Scala, Kotlin
* Spring, Spring Boot, Spring WebFlux
* Akka (HTTP, Streams, Actors)
* Play Framework
* Hibernate, JPA
* Project Lombok
* Guice (small apps)
* Netty
* Resilience4J
* JUnit, AssertJ
* Spring Integration
* Activiti BPM
* Apache Spark
* Maven, Gradle

### Systems

* Go
* Rust (basic)

### Databases

* PostgreSQL / Amazon Redshift
* MySQL
* SQL Server
* Oracle
* MongoDB
* Cassandra
* DynamoDB
* Redis
* Elasticsearch

### Messaging

* Kafka

### Cloud & Infrastructure

* AWS
* GCP
* Docker, Docker Compose
* Kubernetes
* Terraform
* Helm

### DevOps / CI

Experience across three generations of CI/DevOps/GitOps:
  1. Jenkins/Hudson, Shell scripts, Ansible
  1. Codefresh, GitHub Actions
  1. Kargo/Argo

### Linux/BSD

* Daily driver: Debian
* Also used extensively: Arch, Gentoo, FreeBSD

### Scripting

* Python
* Ruby

### Frontend

* JavaScript 
* TypeScript
* Angular

### Languages

* English (B2)
* Russian (native)

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


