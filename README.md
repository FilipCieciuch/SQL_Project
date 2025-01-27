# Project: Job Market Analysis

## Introduction
The modern job market is constantly evolving, with new roles and skills emerging as technology advances and industries adapt. Understanding which skills are in demand and which roles offer the highest compensation is critical for job seekers, educators, and policymakers. This project leverages SQL to analyze job market data, uncovering insights about top-paying roles, highly demanded skills, and optimal skillsets for maximizing career opportunities.
SQL queries? Check them out there: [project_sql folder](/sql_codes/)

## Background
The job market is driven by a combination of supply and demand for skills, industry-specific requirements, and economic trends. By analyzing job-related data, it is possible to identify patterns that inform career decisions. This project was initiated to bridge the gap between raw data and actionable insights, enabling users to understand the dynamics of salaries and skill demand in a data-driven manner.

The dataset used in this project contains information about various job roles, associated skills, and salary details. Using SQL queries, we processed this data to extract meaningful trends and present them in an accessible format.


## Tools I Used
This analysis relied on the following tools:
- **SQL**: For querying and analyzing the data, extracting patterns, and summarizing insights.
- **CSV Dataset**: A file containing raw data on job roles and salaries, imported into the database for analysis.
- **Database Environment**: PostgreSQL was used to execute the scripts and perform computations.

## The Analysis
The analysis was conducted using a series of SQL scripts, each designed to address a specific question about the job market:

1. **Top-Paying Jobs**:
   - Query: `1_top_paying_jobs.sql`
   - This script ranks job titles by their average salaries, helping identify roles with the highest earning potential.

2. **Skills for Top-Paying Jobs**:
   - Query: `2_top_paying_job_skills.sql`
   - This query maps job roles to their associated skills and ranks them by salary, providing insight into which skills contribute most to high pay.

3. **Most Demanded Skills**:
   - Query: `3_top_demanded_skills.sql`
   - Analyzes the frequency of skills mentioned in job postings to highlight those with the highest demand.

4. **Top-Paying Skills**:
   - Query: `4_top_paying_skills.sql`
   - Focuses on isolating skills that offer the highest salaries, regardless of their overall demand.

5. **Optimal Skillsets**:
   - Query: `5_optimal_skill.sql` and `5.1_optimal_skill_shorter.sql`
   - These scripts identify the best combination of skills that maximize salary potential while maintaining relevance in the job market.

By running these queries, users can gain a comprehensive understanding of the interplay between job roles, skills, and compensation.

## What I Learned
Through this project, I gained valuable insights into:
- The strong correlation between specific skills and salary levels.
- How certain roles consistently offer higher pay due to their specialized nature.
- The importance of analyzing both demand and salary data when identifying optimal skillsets.
- The power of SQL in transforming raw data into actionable insights.

## Conclusions
This project demonstrates the value of data-driven analysis in understanding the job market. By applying SQL queries to real-world data, I was able to uncover critical trends that can inform career decisions and strategic planning for professionals and organizations.

Future extensions of this project could include:
- Expanding the dataset with additional data sources for more comprehensive insights.
- Automating the analysis process using Python or similar programming languages.
- Visualizing the results using tools like Tableau or Matplotlib for better communication of findings.

This project is a stepping stone toward making the job market more transparent and accessible for everyone. Contributions and feedback are welcome to further refine and expand its scope.

