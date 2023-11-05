# Business-360-Insight

## Project Overview
AtliQ Hardware, amidst rapid growth and increased market competition, is harnessing the power of data analytics with Power BI to enhance data-driven decision-making across finance, sales, marketing, and supply chain operations. This project is designed to address stakeholders' queries by delivering comprehensive insights through meticulously crafted visualizations and reports.

## Learning and Development
This project was developed while following the Codebasics Power BI Course, which can be found [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)

## Tech Stacks
- SQL
- Power BI Desktop
- Excel
- DAX language

## Power BI Techniques Learned
- Crafting calculated columns and creating measures with DAX
- Data modeling essentials
- Utilizing bookmarks for visual transitions
- Navigating pages with interactive buttons
- Applying the `DIVIDE` function to avert division errors
- Generating a date table using M language
- Dynamic report titling based on active filters
- Integrating KPI indicators for at-a-glance insights
- Conditional formatting for visual enhancement
- Data validation techniques for ensuring accuracy
- Power BI services for publishing and sharing reports

## Business-Related Terms and Concepts
- Understanding financial metrics such as gross price, pre/post-invoice deductions, and net sales
- Grasping the nuances of COGS, YTD, and YTG
- Comprehending the sales channels including direct, retailer, and distributors

## Company Background - AtliQ Hardware

AtliQ Hardware has experienced significant growth in recent years, expanding its global footprint. The company specializes in the sale of computers and computer accessories, operating through three primary sales channels:

- **Retailers:** Partnering with various retail outlets to reach customers where they shop.
- **Direct Sales:** Selling directly to consumers through corporate sales teams and online platforms.
- **Distributors:** Working with a network of distributors to manage bulk sales and logistics.

## Project Kickoff
Before diving into the dashboard creation, it's crucial to align on the project's objectives, success metrics, timelines, stakeholder expectations, potential challenges, and data requirements.

## Questions to Consider Before Dashboard Development
- What are the objectives of building this Power BI dashboard?
- How will we measure the success of this project?
- What is the expected timeline for project completion?
- Are stakeholders expecting a preview before the final release?
- What hopes and fears do stakeholders have regarding this dashboard?
- Who will use the dashboard and for what purpose?
- What are the design and view preferences from stakeholders?

## Dataset Overview

A clear understanding of the available data sets a strong foundation for meaningful analysis. Before diving into the analytics, it's essential to grasp what data is at hand.

### Dimension Tables

These tables contain static data such as details of customers and products.

- `dim_customer`:
  - Markets: 27 distinct markets (e.g., India, USA, Spain)
  - Customers: 75 distinct entities across markets
  - Platforms: Brick & Mortar (Physical stores), E-commerce (Online stores like Amazon, Flipkart)
  - Channels: Retailer, Direct, Distributors

- `dim_market`:
  - Markets: 27 distinct markets (e.g., India, USA, Spain)
  - Sub-zones: 7 sub-zones
  - Regions: APAC, EU, LATAM, and others

- `dim_product`:
  - Divisions: P&A (Peripherals & Accessories), PC (Personal Computers), N&S (Networking & Storage)
  - Categories: 14 different categories, including Internal HDD, Keyboards, etc.
  - Variants: Multiple variants available for each product type

### Fact Tables

These tables contain dynamic data regarding transactions and forecasts.

- `fact_forecast_monthly`:
  - Purpose: To anticipate customer demand, enhancing satisfaction and reducing storage costs
  - Structure: Denormalized for analytical efficiency, with dates standardized to the month's start
  - Contents: Includes all necessary columns, ending with the forecast quantity needed by the customer

- `fact_sales_monthly`:
  - Similar to `fact_forecast_monthly` but concludes with the actual quantity sold rather than the forecast

### Additional Tables

- `freight_cost`: Details of travel and additional costs for each market, organized by fiscal year
- `gross_price`: Lists gross prices associated with each product code
- `manufacturing_cost`: Contains manufacturing cost per product code, detailed yearly
- `pre_invoice_deductions`: Details of pre-invoice deduction percentages for each customer, by year
- `post_invoice_deductions`: Provides information on post-invoice deductions and other related details

This thorough dataset serves as the backbone for the analysis performed in this project.

## Data Model

Data modeling is the bedrock upon which our entire reporting structure is built. It is the framework that dictates how data is connected, processed, and presented in the form of visuals.

You can view the data model ([Data Model](https://github.com/zalakbhagat/Business-360-Insight/blob/main/Data%20Model.png)).

## Dashboard Views

The dashboard is segmented into specialized views, each providing a unique lens through which to interpret AtliQ Hardware's operational data:

You can view the data model ([Dashboard View](https://github.com/zalakbhagat/Business-360-Insight/blob/main/Home%20view.png)).

### 📊 Finance View
Dive deep into financial health with detailed P&L analysis, net sales trends, top-performing products and clients, and essential financial insights that drive strategic planning.

You can view the data model ([Finance View](https://github.com/zalakbhagat/Business-360-Insight/blob/main/Finance%20view.png)).

### 📈 Sales View
Explore in-depth customer and product performance, engage with matrix analysis, and understand the unit economics that shape profitability and sales strategies.

You can view the data model ([Sales View](https://github.com/zalakbhagat/Business-360-Insight/blob/main/Sales%20View.png)).

### 📣 Marketing View
Unlock critical product and market insights, analyze gross margin and net profit percentages, and dissect segment-specific metrics to optimize marketing initiatives.

You can view the data model ([Marketing View](https://github.com/zalakbhagat/Business-360-Insight/blob/main/Marketing%20View.png)).

### 🌐 Supply Chain View
Investigate forecast accuracy and errors, glean customer insights, and evaluate key product metrics to streamline supply chain processes and enhance operational efficiency.

You can view the data model ([Supply Chain View](https://github.com/zalakbhagat/Business-360-Insight/blob/main/Supply%20Chain%20view.png)).

### 🔍 Executive View
Gain a high-level perspective on business zones, revenue streams, gross margin and net profit percentages, as well as market share trends that inform executive decision-making.

You can view the data model ([Executive View](https://github.com/zalakbhagat/Business-360-Insight/blob/main/Executive%20view.png)).

Each view is designed to support comprehensive analysis and foster data-driven decisions across all levels of the organization.

## Live Report

To see the live version of the Power BI dashboard, please visit the following link:

[View Live Report](https://app.powerbi.com/view?r=eyJrIjoiZjM5MDhlM2UtMmFlYy00ZjdjLWEwYTctN2FhM2Q4N2JlZDhhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
