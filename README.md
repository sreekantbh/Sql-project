# Sql-project
Project Title: Licious Product Dissection & Data Architecture Case Study

Project Overview
This project is a product dissection and database schema design case study focused on Licious, a hyperlocal Direct-to-Consumer (D2C) food-tech platform.
The objective is to understand how data architecture enables Licious to solve real-world challenges such as freshness tracking, cold-chain logistics, and hyperlocal delivery while maintaining scalability.

The study deep-dives into Licious’s Farm-to-Fork model and translates business requirements into a SQL-ready relational schema with traceability and operational logic in mind 

🎯 Problem Statement

Traditional meat supply chains in India suffer from:

* Poor hygiene and lack of quality assurance

* Inconsistent availability of specific cuts

* The “Fresh vs Frozen” dilemma

This project explores how data modeling and system design can address these issues at scale for a D2C platform like Licious.

🔍 Key Features Analyzed

* Farm-to-Fork owned supply chain

* 0–4°C cold-chain freshness model

* Hyperlocal processing hubs

* Specific meat cuts & categorization

* Express delivery (90–120 minutes)

* Subscription-based loyalty program (Meatopia)

* Inventory batch-level traceability

🧠 Case Study Scenario

“Weekend Biryani” Use Case
A real-world user journey demonstrating how Licious solves availability, freshness, and convenience problems using:

* Curated product cuts

* Batch-level inventory

* Hyperlocal fulfillment

* Subscription-based delivery benefits

🗄️ Database Schema Design

The schema is designed to support freshness, traceability, and hyperlocal delivery.

Core Entities:

* User

* Address

* Product

* Inventory_Batch (batch-level freshness tracking)

* Hub (hyperlocal processing centers)

* Order

* Order_Items

* Subscription (Meatopia)

  Key Design Highlights:

* Batch-level inventory instead of generic stock counts

* Order-to-batch linkage for full traceability

* Hub-based availability for hyperlocal delivery

* Subscription logic for automated delivery fee handling

📊 ER Diagram

An Entity-Relationship Diagram (ERD) visually represents:

* One-to-many relationships between hubs and inventory batches

* Product replenishment through multiple batches

* Order item traceability back to sourcing batches

This ensures quality control, freshness guarantees, and operational transparency.

🛠️ Tools & Concepts Used

* SQL-based relational data modeling

* Entity-Relationship Design

* Product dissection methodology

* Supply chain & logistics modeling

* Hyperlocal system design principles

📈 Business Impact

The proposed data architecture enables:

* Freshness tracking from farm to customer

* Hyperlocal availability filtering for fast delivery

* Quality issue traceability to specific batches

* Customer retention through subscription-based incentives

