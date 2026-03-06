# Data Analytics

When creating the Wings of Help project, I worked closely with the team. At the initial stage, I described the project idea, defined the strategic approach and planning stages, and prepared the Software Requirements Specification.

The main KPIs and metrics were developed, and together with the designer, key user flows and events for analytics were agreed upon. Additionally, analytical hypotheses were formulated and statistical methods for their verification were described.

The next stage was the development of a dataset for the project in Python, taking into account the defined KPIs, metrics, and database structure, which was prepared by the front-end developer. The generated dataset consists of four tables: help_categories.csv, users.csv, help.csv, and events.csv.

Exploratory data analysis (EDA) was also conducted using Python tools (Pandas, NumPy, Matplotlib, Seaborn), statistical significance testing was performed, and visualizations of the results were created.

As part of the analytical part of the project, the structure of two dashboards was developed, which were implemented in Tableau and Power BI.

# Table of Contents
 - [Strategic approach and project planning](#strategic-approach-and-project-planning)
 - [Software Requirements Specification](#software-requirements-specification-srs)
 - [Identifying key user flows and events](#identifying-key-user-flows-and-events)
 - [Developing basic KPIs and metrics](#developing-basic-kpis-and-metrics)
 - [Creating hypotheses for A/B tests](#creating-hypotheses-for-ab-tests)
 - [Statistical Methods for Product Analytics](#statistical-methods-for-product-analytics)
 - [Development of the Wings of Help Dataset](#development-of-the-wings-of-help-dataset)
 - [Exploratory Data Analysis and Visualization in Python](#exploratory-data-analysis-and-visualization-in-python)
 - [Development of a Tableau Dashboard](#development-of-a-tableau-dashboard)
 - [Development of a Power BI Dashboard](#development-of-a-power-bi-dashboard)
 - [Tools and Skills Gained](#tools-and-skills-gained)

## Strategic approach and project planning
[Link to the project plan](https://docs.google.com/document/d/1O2il_e48FGHaMWdllqT1MlPGp07ZM3OkoiIAKDUbUos/edit?usp=sharing)

Goal: To create an efficient and user-friendly web platform that will ensure fast, transparent and organized coordination of humanitarian assistance between those in need and volunteers.

SMART goals: Develop an MVP within one month with basic features (user registration, request creation, request viewing/filtering, and status updates), ensure interface adaptation for mobile and desktop devices, and implement basic security measures to protect user data.

## Software Requirements Specification (SRS)
[SRS document link](https://docs.google.com/document/d/167jKUfHUJSwIn6rO1XJVDriEiqZ9lLps/edit?usp=sharing&ouid=104269468961255412319&rtpof=true&sd=true)

The document is a Software Requirements Specification and describes the functional and non-functional requirements for the Wings of Help web platform, designed to coordinate requests and provide assistance by volunteers.  

The purpose of the Wings of Help web service is to facilitate effective collaboration between individuals or organizations in need of assistance and volunteers providing assistance. The document is intended for stakeholders, developers, designers, testers, analysts, and other team members involved in the project.

## Identifying key user flows and events
[View the document](https://docs.google.com/document/d/1Q48osqTN8kndkOjW3UQNAatLBwF5dd5dxVau_tYyhdY/edit?usp=sharing)

This document defines key user flows and the event model for the web service to support accurate product and event analytics. It helps measure the effectiveness of key user scenarios and ensures consistency between UX, backend, and data analytics. The document also prepares the system for implementing event tracking.

## Developing basic KPIs and metrics
[View the document](https://docs.google.com/document/d/1Km0dKCElqv5qamU37tBzniLV-7p6ZAL2ntk_doPj2rA/edit?usp=sharing)

The purpose of this document is to define key performance indicators (KPIs) and analytical metrics for evaluating the effectiveness of the Wings of Help web service. These metrics help assess platform performance and the quality of interaction between users, volunteers, and the system. They are also used for building dashboards, monitoring performance, and supporting product and business decisions.

## Creating hypotheses for A/B tests
[View the document](https://docs.google.com/document/d/1O9597Io1CI1i9OXtFHM671hNIhn2Lo0czgMCtUnTqNM/edit?usp=sharing)

A/B testing in the Wings of Help web service is planned to be used to test product hypotheses aimed at improving platform performance and user experience. It helps to reduce the time between creating a request and providing assistance, increase the number of completed requests, and increase volunteer engagement. This approach supports data-driven decision-making and reduces reliance on subjective assumptions.

## Statistical Methods for Product Analytics
[View the document](https://docs.google.com/document/d/1TjVWm74JYVtXbcqFHbTy41QA0K4anysEmGUgmApyCa0/edit?usp=sharing)

This document describes statistical methods used to analyze product analytics for the “Wings of Help” web service. These methods support accurate KPI analysis and evaluation of A/B test results to enable data-driven product decisions. The document also helps ensure the correct use of statistical tests and a consistent analytical approach across teams.

## Development of the Wings of Help Dataset
[Open Dataset Generation Code](https://colab.research.google.com/drive/1LMIO7Z1wkY_GGSqaoilM2CyTbFK2JF2e?usp=drive_link)

The Wings of Help web service provides interaction between people or organizations in need of help and volunteers, allowing users to create, publish, view, and manage requests for help. The platform allows requests to be created, processed by volunteers, and content to be moderated by administrators.  
The dataset was created to simulate the platform, test the functionality of the web service, analyze the interaction between users and volunteers, and for further research related to optimizing the processing of help requests and scaling the system. Currently, the web platform is developed as an MVP with basic functionality for quick launch and scalability in the future.

Developed dataset for the Wings of Help web service: 
 - Help Categories Table  
[View the help_categories.csv](https://drive.google.com/file/d/12aZfMzEf5u--WN9sBAJs7qq0ZVtFtjSj/view?usp=sharing)

 - Users Table  
[View the users.csv](https://drive.google.com/file/d/12aZfMzEf5u--WN9sBAJs7qq0ZVtFtjSj/view?usp=sharing)

 - Help Table  
[View the help.csv](https://drive.google.com/file/d/1NWqw6SPQ-ZxeKBiSKRloT8C-2ZDEWctB/view?usp=sharing)

 - Events Table  
[View the events.csv](https://drive.google.com/file/d/1rewutkypinj0Z9lnEsFM4HIpmeF5lCHh/view?usp=sharing)
   
## Exploratory Data Analysis and Visualization in Python
[Open Notebook](https://colab.research.google.com/drive/1xdy3zlf1FJd1i7pZ-cp4Q3nvApYhaDPM?usp=drive_link)

The Wings of Help web service enables interaction between people or organizations in need of help and volunteers through a centralized platform for managing requests for help. The project dataset was created in Python and follows the Postgres SQL database structure, key performance indicators (KPIs), and metrics defined in the project documentation.

## Development of a Tableau Dashboard
[View the document](https://docs.google.com/document/d/1mM0jjqHDccpMarAl8XXr5woU2CP8WEb6TKfbxMJIYYw/edit?usp=sharing)

[Link to the Dashboard on Tableau Public](https://public.tableau.com/app/profile/oksana.olar/viz/WingsofHelpAnalyticsMVP/WingsofHelpPlatformPerformanceUserAnalytics)

This dashboard provides a comprehensive analytical overview of the Wings of Help platform, focusing on user growth, engagement, operational efficiency, and supply-demand balance between requests and offers.  
It is designed to support product and operational decision-making by tracking platform performance across acquisition, activation, engagement, and fulfillment stages. The developed Wings of Help | Platform Performance & User Analytics dashboard is shown in Fig. 1.   

<img width="1499" height="1749" alt="Copy of Wings of Help Tableau" src="https://github.com/user-attachments/assets/dd823b83-21d5-4572-a481-86883197cc8d" />

Fig. 1. Wings of Help | Platform Performance & User Analytics

The web platform of the “Wings of Help” demonstrates a stable growth of users and a gradual increase in their involvement: Engagement Rate has increased to 45%, and WAU is stable without sharp declines. This indicates the formation of an active user base and the growth in value of this web service.   
The distribution by roles reveals a significant imbalance between demand and supply, as the share of requests and users in need of help significantly exceeds the number of available volunteers.   
The main need at the moment is to scale up the offers and improve the matching processes, since a significant share of requests remains in the new status. The web platform has proven demand and positive development dynamics, so the next stage is to strengthen the volunteer base and increase the conversion of interactions for more effective closing of requests for help.  

## Development of a Power BI Dashboard
[View the document](https://docs.google.com/document/d/1YSGfG6Q_suBsq-ZqdDYUU1btYVzp1ffhKQPFzbhEvKw/edit?usp=sharing)

This dashboard is designed for a comprehensive analysis of the effectiveness of the Wings of Help web platform. It allows you to assess the balance between demand and supply of assistance, the level of coverage of requests by volunteers, the speed of response to requests, and the overall operational effectiveness of the case processing process. The use of key KPIs and analytical visualizations allows you to identify bottlenecks in the platform's work, identify risk areas, and formulate management recommendations for improving the quality of the web service. The developed Wings of Help: Platform Health & Demand-Supply Analysis dashboard is shown in Fig. 2. 

<img width="1127" height="729" alt="Wings of Help Power BI" src="https://github.com/user-attachments/assets/26310f3b-8d13-42d4-9f40-12f58b986416" />

Fig. 2. Wings of Help: Platform Health & Demand-Supply Analysis


As a result of building the dashboard, it was found that the Wings of Help platform operates in a state of stable imbalance between demand and supply. In particular, the number of requests for help consistently exceeds the number of offers of help by more than two times, which leads to the accumulation of unmet demand.  
The analysis of process efficiency revealed that only a portion of the created requests is processed, with a small percentage reaching completion, indicating a bottleneck at the stage of fulfilling demand by volunteers. At the same time, the average and median time to take a request into work is about 34.5 hours, which is a sign of a stable, but not instantaneous, response speed. The presence of cases with a delay of up to 72 hours confirms the uneven load on volunteers, low volunteer involvement, or limited resources.  
Therefore, the key insights are the structural shortage of supply, the need to increase the level of volunteer involvement, and the potential for optimizing the response process to reduce user waiting times.  

## Tools and Skills Gained

**Data Analytics & Programming**
 - Python (Pandas, NumPy) - used for dataset generation, data manipulation, and preparation of analytical datasets.
 - Exploratory Data Analysis (EDA) - performed statistical exploration of the dataset, identification of patterns, distributions, and anomalies.
 - Data Visualization (Matplotlib, Seaborn) - created visualizations to analyze user behavior, request processing dynamics, and platform performance.
 - Statistical Analysis - applied statistical significance testing and analytical methods to validate product hypotheses and evaluate platform metrics.

**Data Modeling & Dataset Development**
 - Dataset Design - designed a structured dataset that simulates the functionality of the web platform.
 - Relational Data Modeling - created interconnected tables (users, help, help_categories, events) aligned with a PostgreSQL-style database structure.
 - Synthetic Data Generation - generated realistic test data to simulate platform interactions between users and volunteers.

**Product Analytics**
 - KPI and Metrics Development - defined key performance indicators for measuring platform growth, engagement, and operational efficiency.
 - User Behavior Analytics - analyzed user interactions, volunteer engagement, and request lifecycle events.
 - Event Tracking Design - developed an event model to support product analytics and measure key user flows.
 - A/B Testing - formulated analytical hypotheses and defined metrics and statistical methods for testing product improvements.

**Business Intelligence & Data Visualization**
 - Tableau Public - designed an analytical dashboard to monitor platform performance, user engagement, and demand-supply balance.
 - Power BI - built an operational analytics dashboard to evaluate platform health, request processing efficiency, and response times.
 - Dashboard Design - structured analytical dashboards to support data-driven product and operational decisions.

**Product & Project Analytics**
 - Product Thinking - defined analytical goals aligned with product strategy and platform development stages.
 - User Flow Analysis - mapped key user journeys and platform interactions to support event analytics.
 - Analytical Documentation - created structured analytical documentation including KPIs, statistical methods, and analytical hypotheses.

**Collaboration & Analytical Planning**
 - Cross-functional collaboration - worked with designers and developers to align analytics, UX flows, and database structure.
 - Strategic planning - participated in defining the product concept, MVP scope, and analytical framework for the project.
