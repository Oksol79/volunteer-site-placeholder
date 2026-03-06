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
 - [Developing a dashboard structure in Tableau]()


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
[Link to Python code for creating the Wings of Help dataset](data-analytics/Python%20Code%20for%20Creating%20the%20Wings%20of%20Help%20Dataset.ipynb)

The Wings of Help web service provides interaction between people or organizations in need of help and volunteers, allowing users to create, publish, view, and manage requests for help. The platform allows requests to be created, processed by volunteers, and content to be moderated by administrators.  
The dataset was created to simulate the platform, test the functionality of the web service, analyze the interaction between users and volunteers, and for further research related to optimizing the processing of help requests and scaling the system. Currently, the web platform is developed as an MVP with basic functionality for quick launch and scalability in the future.

Developed dataset for the Wings of Help web service: 
 - Help Categories Table  
[View the help_categories.csv](https://drive.google.com/file/d/1Qm919Z_XPJ2m1Gp9lkIfkjmEfUH5_Bs4/view?usp=sharing)

 - Users Table  
[View the users.csv](https://drive.google.com/file/d/12aZfMzEf5u--WN9sBAJs7qq0ZVtFtjSj/view?usp=sharing)

 - Help Table  
[View the help.csv](https://drive.google.com/file/d/1NWqw6SPQ-ZxeKBiSKRloT8C-2ZDEWctB/view?usp=sharing)

 - Events Table  
[View the events.csv](https://drive.google.com/file/d/1rewutkypinj0Z9lnEsFM4HIpmeF5lCHh/view?usp=sharing)
   
## Exploratory Data Analysis and Visualization in Python
[Link to Exploratory Data Analysis and Visualization in Python](data-analytics/Exploratory%20Data%20Analysis%20and%20Visualization%20in%20Python.ipynb)

The Wings of Help web service enables interaction between people or organizations in need of help and volunteers through a centralized platform for managing requests for help. The project dataset was created in Python and follows the Postgres SQL database structure, key performance indicators (KPIs), and metrics defined in the project documentation.

## Developing a dashboard structure in Tableau
[View the document](https://docs.google.com/document/d/1mM0jjqHDccpMarAl8XXr5woU2CP8WEb6TKfbxMJIYYw/edit?usp=sharing)

This dashboard provides a comprehensive analytical overview of the Wings of Help platform, focusing on user growth, engagement, operational efficiency, and supply-demand balance between requests and offers.
It is designed to support product and operational decision-making by tracking platform performance across acquisition, activation, engagement, and fulfillment stages.





## Tools Used
- SQL - 
- Python
- Tableau Public
- Excel

## Contents
- SQL queries used for analysis
- Dataset description
- Tableau dashboard
- Analytical insights
