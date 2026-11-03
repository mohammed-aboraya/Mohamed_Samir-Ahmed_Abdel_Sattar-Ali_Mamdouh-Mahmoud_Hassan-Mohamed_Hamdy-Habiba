 Store Sales Data Analysis
 Project Overview:
This project focuses on analyzing the Superstore Sales Dataset using Power BI. The goal is to understand sales performance, identify trends, compare different products and regions, and present useful insights through data analysis and visualizations.
 
 1. Project Planning & Management
Summary:

This document explains how the project will be organized and completed. It includes the project objectives, scope, timeline, expected deliverables, and distribution of tasks among team members. It also identifies possible risks and how to deal with them, along with the KPIs that will be used to evaluate sales performance and track the project's progress.

Team Members & Responsibilities:
- Mahmoud Hassan: Worked on organizing project tasks, planning the timeline, and defining the project scope.
- Mohamed Samir Mohamed Hassan (Team Leader): Worked on coordinating the team, organizing the project plan, and defining KPIs and risk management plans.

#2. Literature Review

Summary:

This document discusses the project background and the Superstore sales dataset. It covers feedback and evaluation, suggested improvements to the project, and the criteria used for final project grading. It helps the team understand what needs to be evaluated, which improvements can be made, and what aspects should be considered when assessing the project.

Team Members & Responsibilities:
- Mohamed Hamdy: Worked on reviewing information related to sales analysis and identifying relevant findings.
- Ali Mamdouh: Worked on organizing the review, documenting suggested improvements, and preparing the evaluation criteria.

3. Requirements Gathering

Summary:

This document explains what the project needs to include before starting the analysis and dashboard development. It identifies the stakeholders, describes user stories and use cases, and lists the functional and non-functional requirements. It also identifies the KPIs and analyses that can be created from the available dataset, such as total sales, total orders, average order value, customer analysis, and sales comparisons by product, category, region, and segment. Finally, it outlines the assumptions and constraints that must be considered during the project.

Team Members & Responsibilities:
- Ahmed Abd El Sattar: Worked on identifying stakeholders, writing user stories and use cases, and documenting functional requirements.
- Habiba: Worked on documenting non-functional requirements, identifying relevant KPIs, and organizing the requirements document.

Team Collaboration
All team members contribute to reviewing the documents, sharing feedback, and preparing the project deliverables.
___________________________________________________________________________________________________________________________________________________________________
Phase 2 – System Analysis & Design
Project Overview
This project aims to analyze the Superstore Sales Dataset to evaluate sales performance, identify trends, and generate insights that support better business decisions using Power BI.
1. Problem Definition
The project focuses on transforming raw sales data into meaningful information by analyzing orders, customers, products, sales, and geographical performance.
Main Objectives:
- Analyze sales and order performance.
- Identify top-selling products and categories.
- Compare sales across regions and customer segments.
- Track sales trends over time.
- Develop interactive Power BI dashboards.
 2. Use Case Diagram
Defines how the **Business User / Sales Manager** interacts with the system through:
- View Sales Dashboard and KPIs.
- Analyze Sales by Region.
- Analyze Products and Categories.
- Analyze Customer Segments.
- Analyze Sales Trends.
- Apply Filters and View Insights.
3. Entity Relationship Diagram (ERD)
The current data model consists of two tables:
- Clean Data:Contains order, customer, product, sales, and geographical information.
- DateTable:Contains Date, Day, Month, Month Number, Quarter, and Year.
Relationship:
`DateTable[Date] (1) → Clean Data[Order Date] (*)`
The relationship supports time-based sales analysis.
 4. Data Flow Diagram (DFD)
The DFD describes the main data processing workflow:
1. Import Data.
2. Clean & Transform Data.
3. Model Data.
4. Analyze & Visualize Data.
Both Level 0 and Level 1 diagrams were prepared to represent the system overview and detailed processes.
 5. Dashboard Wireframes
Initial layouts were designed for three dashboard pages:
- Sales Overview:** Overall sales performance, KPIs, trends, and regional analysis.
- Product Analysis:** Product rankings, categories, and sub-categories.
- Customer & Geographic Analysis:** Customer segments, top customers, and geographical sales distribution.
 6. Technology Stack
   Technology : Purpose 
 Microsoft Excel : Data source and inspection 
 Power Query : Data cleaning and transformation 
 Power BI Desktop : Datamodeling and visualization 
 DAX : Measures and KPI calculations 
 GitHub : Documentation and collaboration 
 
Phase 2 Deliverables
- Problem Definition
- Use Case Diagram
- ERD
- DFD Level 0 & Level 1
- Dashboard Wireframes
- Technology Stack
Next Phase: Implementation
Data preparation, modeling, DAX calculations, business insights, and Power BI dashboard development.
Program:Digital Egypt Pioneers Initiative (DEPI)  
Project: Store Sales Data Analysis
