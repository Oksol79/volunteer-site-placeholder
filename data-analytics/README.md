# Data Analytics

When creating the Wings of Help project, I worked closely with the team. At the initial stage, I described the project idea, defined the strategic approach and planning stages, and prepared the Software Requirements Specification.

The main KPIs and metrics were developed, and together with the designer Sofia Kolomoyets, key user flows and events for analytics were agreed upon. Additionally, analytical hypotheses were formulated and statistical methods for their verification were described.

The next stage was the development of a dataset for the project in Python (7), taking into account the defined KPIs, metrics, and database structure, which was prepared by the front-end developer Anton Blyznyuk. The generated dataset consists of four tables: help_categories.csv (8), users.csv (9), help.csv (10), and events.csv (11).

Exploratory data analysis (EDA) was also conducted using Python tools (Pandas, NumPy, Matplotlib, Seaborn), statistical significance testing was performed, and visualizations of the results were created (12).

As part of the analytical part of the project, the structure of two dashboards (13) was developed, which were implemented in Tableau (14) and Power BI (15).

# Table of Contents
 - [Strategic approach and project planning](#strategic-approach-and-project-planning)
 - [Software Requirements Specification](#software-requirements-specification-srs)
 - [Identifying key user flows and events](#identifying-key-user-flows-and-events)
 - [Developing basic KPIs and metrics](#developing-basic-kpis-and-metrics)
 - [Creating hypotheses for A/B tests](#creating-hypotheses-for-ab-tests)
 - [Statistical Methods for Product Analytics](#statistical-methods-for-product-analytics)
 - 


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
