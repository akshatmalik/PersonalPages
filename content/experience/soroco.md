+++
authors = ["Akshat Malik"]
title = "Scout - Soroco"

date = "2018-01-01"
description = "Experience at Soroco"
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

# Scout - Soroco

[//]: # (![Soroco Logo]&#40;/img/soroco_logo.png&#41;)

Soroco was the first company I worked at after graduating from college. I got a chance to learn a lot about how to build a product from scratch, and how to scale it to a large number of users. We primarily worked in Python as the main language along with Django and Flask. 

**Technologies Used:** Python - Django & Flask; go; Docker, Ansible, RabbitMQ & PostgreSQL; Qlik


## Data Analysis Pipeline 📊️ 🚰

[//]: # (One the key contributions was working on a user data analysis pipeline which would allow the data analysis team to move faster. Our work allowed the processing power to **increase by 40 times**, increasing the amount of data that could be processed. The data pipeline needed to be created with the following features:)

A significant contribution I made at Soroco was the development of a user data analysis pipeline. This system was designed to empower the data analysis team with enhanced processing capabilities, leading to a **40-fold increase in processing power**. This augmentation enabled the handling of substantially larger data sets. The pipeline was engineered with the following key features:

[//]: # (- **Scalable** - The pipeline should be able to scale to a large number of users. )

[//]: # (- **Flexible** - As the analysis process was always changing, the tool needed to be flexible to enough to allow for changes in the analysis process and the data being processed.)

[//]: # (- **Retryable** - Given the analysis process was ever-changing, the analytics team should be able to rerun certain parts of the process again, without running the entire process.)

- **Scalability**: It was vital that the pipeline could handle an expanding user base efficiently.
- **Flexibility**: Given the dynamic nature of our data analysis processes, the pipeline was designed to be adaptable to continuous changes in both the analysis methods and the nature of data processed.
- **Retryable**: To accommodate the evolving analysis procedures, it was imperative that the pipeline allowed for specific segments to be reprocessed without necessitating a complete rerun.

[//]: # (The analysis pipeline worked as factory pipeline where each analysis process was divided into small, parallel running sub-problems, allowing for parallel processing. This effort greatly eased the work of the data analysis team, allowing them to focus on the analysis process rather than the infrastructure.  )

The architecture of this pipeline mirrored that of a factory line, where each analytical process was subdivided into smaller, parallel tasks. This design facilitated simultaneous processing and significantly simplified the data analysts' workflow, enabling them to concentrate more on analytical insights rather than the underlying infrastructure.

## User Portals 🖥️

[//]: # (The user data that was analysed needed to be shown to the end users. I worked on the user portal which was designed to onboard, manage and configure users, while also showing the data collected. The portal was built using Angular, Django and PostgreSQL. I worked on various feature development for the user portal, including:)

[//]: # (- Onboarding users)

[//]: # (- Managing users)

[//]: # (- Viewing the data collected for the users)

[//]: # ()
[//]: # (To serve users in a promptly, we developed some data transformation steps which populated the data from the analysis pipeline to our user portal. )

An integral part of my role involved showing the analyzed user data. I was involved in developing a user portal written in go, an interface for user onboarding, management, and configuration, as well as for displaying the processed data. The technology stack for this included Angular, Django, and PostgreSQL. My contributions encompassed:

- Onboarding new users onto the platform.
- Managing user profiles and access.
- Presenting analyzed data to users in a coherent and user-friendly format.

We also developed and integrated data transformation steps that seamlessly transferred data from the analysis pipeline to the user portal, ensuring timely data availability.



## Operations 🧑‍🔧️

[//]: # (I have keep interest in getting involved not only in the development side, but also the operational side of the product. I worked on the following operational tasks:)

[//]: # (- **Monitoring** - Our services were deployed in different environments, therefore to monitor them we needed a centralized monitoring system. We worked on setting up a service health check, a data health check and a service monitoring system which would push updates to the team if any issues were found.)

[//]: # (- - **Dockerize** - I was involved in dockerizing the services, which would allow us to easily deploy the services in different environments. )

[//]: # (- **One-click setup** - To ease the setup of the product, we worked on a one-click setup which would setup the entire product on a single click. This involved setting up the database, the services and the monitoring system and then performing health checks to ensure everything works as expected. )


My interests extended beyond development; I was keenly involved in the operational aspects of our products. My operational responsibilities included:

- **Monitoring**: We set up a comprehensive monitoring system to oversee our services across different environments. This included service health checks, data health monitoring, and a notification system to alert the team of any issues.
- **Dockerization**: I played a key role in dockerizing our services, which streamlined deployment across various environments.
- **One-click Setup**: We developed a one-click setup system to simplify the initial configuration of our product. This encompassed database setup, service initiation, and the integration of our monitoring system, followed by a thorough series of health checks to ensure system integrity and functionality.