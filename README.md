# Telco Project

## Overview

In this project, you will take on the role of a developer at **i2i Systems**, where you are tasked with fulfilling various team requests through database operations. 

You will receive `.csv` files containing telecom-related data to use for answering the provided questions. Please organize your work as follows:
* Save your SQL query solutions in a separate file (e.g., `SOLUTIONS.sql`).
* Include your database table creation scripts, along with their respective indexes and constraints, in another separate file (e.g., `TABLE_CREATION_SCRIPTS.sql`).

You must **fork this repository** and upload your work to your own fork. 
Do **not** attempt to push changes directly to this repository or any of its original branches.

---

## Operational Requirements

1. **Oracle XE Setup**
  * Create a [Docker](https://www.docker.com/products/docker-desktop/) container running **Oracle XE**.  
  * Ensure that the database is properly configured and accessible from your local machine.

3. **DBeaver Installation**
  * Download and install [DBeaver](https://dbeaver.io/).  
  * Establish a connection to your local Oracle XE instance using the DBeaver client.

5. **Data Import**
  * Using the provided `.csv` files containing telecom data, design and **create the necessary tables** in Oracle XE. 
  * **Import the data** from the `.csv` files into your newly created tables, ensuring the schema accurately reflects the provided dataset.

---

## Functional Requirements

You must write SQL queries to address the scenarios listed below. For each query, include comments explaining your approach in **at least three sentences**. Submissions with missing answers or explanations shorter than the required length will **not be evaluated** and will receive **0 points**.

### 1. List subscribers who signed up in the last 6 months.

### 2. Count the number of subscribers who have a fee greater than 200 TL.

### 3. List the subscribers who have an above-average internet usage.

### 4. Identify subscribers with late payments.

### 5. List the top 5 subscribers with the highest call minutes.

---

## 🛠️ Notes

* You have the creative freedom to design the database schema as you see fit, based on the provided dataset.
* Pay close attention to applying the appropriate data types and constraints when creating your tables.
* You may use DBeaver or SQL*Plus to handle the `.csv` data imports into Oracle XE.
* Thoroughly test each query and document both the SQL statement and its resulting output in your submission.
