# SQL-Based Data Analysis Applied on Recruitment Platform Project

## Project Overview
This project represents the data analysis component of my final Bachelor Degree project: developing a full-stack recruitment platform.
SQL was used in communicating with the database built in a MariaDB server, through Data Manipulation Language and queries, to support both the operational workflows of the platform and analytical reporting. The relational database stores structured information across multiple tables, including: candidates and employers, jobs details, job applications and views, connected through primary and foreign keys to ensure data integrity.

## SQL Usage & Key Operations

### User Registration and Authentication
- Created and updated user account information
- User authentication and validation by verifying credentials across multiple database tables.
  
### Job Applications & Data Retrieval
- Retrieved detailed job information for employer listings.
- Generated lists of jobs applied to by candidates using multiple `JOIN` operations.
- Retrieved lists of candidates who applied for specific jobs, accessible to employers.

img cu query si interfata pentru linia 2

### CRUD Operations & Filtering Logic
- Implemented `INSERT`, `UPDATE`, and `DELETE` operations for users, job postings by companies, and applications.
- Ensured data consistency during record creation and updates.
- Built dynamic SQL queries to support filtered and sorted views of candidates, employers, and job postings, allowing up to five simultaneous filters.
<imagine cu exemplu construire query pentru filtrare cu 5 filtre>

---

## Analytical Queries & Insights

  Business-oriented insights were implemented by combining `JOIN`s, `GROUP BY` and aggregate functions, to support informed decision-making in situations such as field research in the context of a career change, or a user's decision to relocate to another county to develop and access a more advantageous salary level.
  The charts created with the help of SQL provide a clear overview of the existing labor market on the platform by highlighting the following aspects:
- highest-paying fields
- district ranking based on average salary levels.
<imagine Salary trend interfata- AverageSalaryQuery decupat>

  Regarding the activity of economic agents on the website, there were 2 statistical investigations added to provide relevant information in making decisions related to the available human resources and the recruitment process. The analysis of candidates distribution organized by county can greatly support companies that plan to expand their business through headquarters, factories or other buildings located in new geographic areas, as they can assess the availability of labor in those areas.

- Distribution of candidates by county and specialization.
<img candidates_count interfata>
tabel cu distribution of candidates poza interfata si poza query din spate>
