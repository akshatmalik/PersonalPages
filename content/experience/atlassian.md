+++
authors = ["Akshat Malik"]
title = "Opsgenie - Atlassian"

date = "2020-06-01"
description = "Experience at Atlassian"
tags = [
    "hugo",
    "markdown",
    "emoji",
]
categories = [
    "syntax",
    "theme demo",
]
series = ["Theme Demo"]
+++

![Atlassian Logo](/img/atlassian_logo.png)

[//]: # (![Opsgenie Logo]&#40;/img/opsgenie_logo.png&#41;)


I started working in Atlassian in May of 2020, in the Opsgenie team. My work was mostly in Java using Spring Boot. During my experience I got to learn how to build critical systems that are used by thousands of people, powered by AWS. 



## Technical Achievements 🧑‍🔧️

Over the course of 2 years, I worked on a variety of projects, some of which are listed below:


**Technologies Used:** Java - Spring Boot; AWS - RDS, DynamoDB, SNS, SQS, Lambda, CloudWatch, S3, EC2, ECS; Monitoring - NewRelic, Splunk; Looker

#### Dashboard Optimization ⏰️


One of the key customer pain points was to optimize the slow load of the dashboards. I was tasked to lead a team of 3 engineers to carry out the efforts to optimize and improve the load time of the dashboards. To carry this out, we had to understand the entire flow of the dashboard load, and identify the bottlenecks, breaking them down into smaller and iterative solutions. 

The bottlenecks identified were:
1. Redundant data being fetched from the database
2. Unoptimized queries and unindexed tables
3. Unoptimized code execution
4. Redundant calls between frontend and backend

Solving these problems allowed us to **reduce the load time of the dashboards by 98%**, resolving a very important pain point for the customers. We also were able to identify unused resources and **save costs by 70%**. 

#### Unifying ETL Pipelines 🚰

Another key feature that I worked on was unifying the **ETL pipelines** for our teams. This feature would allow us to remove redundancy in the current system and further help in extending our pipelines to the new analytics platform being developed. I was tasked with the effort to plan and deliver the task with another engineer. Using AWS Lambda, S3, Firehose, and SNS messages, we were able to **remove redundant code maintenance** in the system and **ease the integration of data into the new analytics platform**.


#### Documentation and Advocacy 📄

I created extensive documentation for the services I owned, this involved writing documentation and commonly done tasks. I also worked on create alert runbooks for the different issues encountered in production for all services. This allowed new developers to be easily onboarded to the team and contribute to on-call. 

I was also the **TechOps Champion** for the team, where I started the practise of monitoring services health each week to ensure repeated issues did not happen. 
Apart from this, I was the **Security Champion** for the team, which involved resolving any security issues that were found in the services. 
Finally, I also conducted **War Games** for the team to ensure that the team was prepared for any incident that might occur.

#### Other Projects ➕➕

##### GDPR Compliance
I worked on project **our services GDPR-compliant**, i.e., it was in the region the user wanted the data to be in. This involved creating scripts that would allow reliable and traceable replication and deletion of user data across regions. Using AWS Step funtions we were able to create a reliable and scalable solution to this problem.

##### Service owner and Feature Development

I was a s**ervice owner for multiple services** in the team. This involved being the point of contact for the service, and being responsible for the service's uptime and reliability. I was also responsible for the feature development of the service, and the roadmap for the service. I developed some other features and did bug fixes for the service as well. I was both the **day and night on-call** for the team. 




[//]: # (gdpr compliacnce)

[//]: # (feature owner )

[//]: # (cost reduction)

[//]: # (Documentation)

[//]: # (Techops, secops, and other things)

[//]: # (advocacy)

