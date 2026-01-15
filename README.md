# customer-behaviour-sql-dannys-diner
Customer behaviour analysis using SQL queries and dashboarding for Danny’s Diner.
# Danny’s Diner Analytics Suite

## Executive Overview

The **Danny’s Diner Analytics Suite** is a compact, insight-driven Power BI dashboard designed to analyze customer behavior, product performance, and spending patterns within a small restaurant environment.

Built from a minimal transactional dataset, this project demonstrates the ability to apply **enterprise-grade BI thinking** — data modeling, analytical rigor, and business storytelling — to a small-scale use case.

The dashboard focuses on three core analytical areas:
- Customer Insights  
- Product Performance  
- Visit & Spending Behavior  

Despite the dataset’s simplicity, the solution follows the same structured approach used in larger, production-level BI systems.

---

## Dashboard Sections

### 1. Customer Insights

**Purpose**  
Understand how customers interact with the diner — frequency of visits, ordering behavior, and total spend.

**Key Features**
- Total customers and visit frequency metrics  
- Days visited by customer to identify loyalty patterns  
- Total amount spent per customer  
- Customer-level order history with item-level detail  

**Business Value**  
Helps identify loyal customers, understand spending behavior, and design targeted promotions or loyalty programs to improve retention.

---

### 2. Product Performance

**Purpose**  
Evaluate which menu items drive customer visits and revenue.

**Key Features**
- Product catalog overview (sushi, curry, ramen)  
- Days visited by product to measure customer pull  
- Product popularity distribution (ramen as the top-ordered item)  
- Item-level order timeline  

**Business Value**  
Supports menu optimization, pricing decisions, and inventory planning by highlighting high-demand items.

---

### 3. Visit & Spending Behavior

**Purpose**  
Reveal temporal patterns in customer visits and spending.

**Key Features**
- Total orders across all customers  
- Daily visit timeline across January and February  
- Customer–product interaction analysis  
- Revenue contribution by customer  

**Business Value**  
Enables better staffing decisions, supply planning, and targeted marketing by identifying peak days and customer preferences.

---

## Data Model & Technical Architecture

### Data Sources
Transactional order data including:
- Customer ID  
- Product ID  
- Product Name  
- Price  
- Order Date (Year, Month, Day)  

### Modeling Approach
- Clean, simple relational structure  
- Calculated measures for:
  - Total Orders  
  - Total Revenue  
  - Days Visited  
  - Customer Spending  
- Date fields structured for time-based analysis  

---

## Design & UX Principles

- Minimalist, clean layout  
- High-contrast KPI cards for quick interpretation  
- Intuitive visuals suited for small datasets  
- Clear storytelling flow from overview → customer → product  

---

## Outcome & Skills Demonstrated

The Danny’s Diner Analytics Suite transforms a small dataset into a meaningful, decision-support analytics tool. It demonstrates:

- Strong analytical storytelling  
- Ability to extract insights from limited data  
- Clean, intuitive dashboard design  
- Practical business value for small-scale operations  

This project showcases adaptability — applying BI fundamentals effectively across both enterprise-level systems and small business environments.

---

## Tools Used
- Power BI  
- DAX  
- Basic Data Modelling  
- Business Intelligence & Data Visualisation  

---

## Author

**Nashra Hareem Masood**  
Supply Chain & Analytics Graduate  
Focus: Business Intelligence, Data Analytics, Decision Support Systems  

---

*This repository serves as a portfolio project highlighting analytical thinking, clarity of insight, and scalable BI design — regardless of dataset size.*
