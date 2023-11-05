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

## Company Background
AtliQ Hardware, now a global presence, retails computer hardware through retailers, direct sales, and distributors. Recently, the company encountered unexpected losses in the American market due to inadequate data-driven decision-making, highlighting the need for an analytics-driven approach to regain competitive advantage.

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

**Key Considerations in Data Modeling:**

- **Structural Integrity:** A well-structured data model ensures the relationship between different data types is logically and efficiently organized.
- **Performance:** Efficient data models significantly enhance the performance of Power BI reports, ensuring swift data refreshes and responsive visualizations.
- **Scalability:** Good data models are scalable, allowing for additional data to be incorporated with minimal rework.

A poorly constructed data model can lead to suboptimal report performance, potentially affecting the user experience and the accuracy of insights derived from the data.


## Views and Features
- Home View: Central navigation to all sections of the report.
- Info, Finance, Sales, Marketing, Supply Chain, Executive, and Products Views: Dedicated pages for detailed insights.
- Support: Information on getting assistance with the dashboard.

## Report Snapshots and GIFs
- Overall Report: `Overall_Report.gif` (Note: Replace with actual GIF or image link)
- Info Page: `Info.gif` (Note: Replace with actual GIF or image link)
- [Continue with other views]

(Note: Replace placeholders with actual data, links, and file paths relevant to your project.)
