# sql-layoffs-data-analysis
SQL-based analysis of global layoffs trends. Used aggregate functions, CTEs, and window functions to identify top affected companies, industries, and yearly trends in layoffs.


# Exploratory Data Analysis on Global Layoffs (SQL Project)

## Project Overview
SQL analysis exploring global layoffs trends to uncover patterns across companies, industries, countries, and years.

## Objectives
- Analyze total layoffs by company, country, and industry
- Identify yearly trends and spikes
- Find companies with 100% layoffs
- Rank top companies per year using CTEs and window functions

## SQL Concepts Used
- Aggregates: SUM(), MAX(), MIN(), AVG()
- Grouping & sorting: GROUP BY, ORDER BY
- Date functions: YEAR(), SUBSTRING()
- CTEs & window functions: DENSE_RANK(), SUM() OVER()
- Filtering and pattern detection

## Dataset
Includes records of layoffs with details on company, industry, country, funding, total laid off, % laid off, and date.

## Key Insights
- Tech and startups saw highest layoffs
- Layoffs peaked in specific post-pandemic years
- High-funded companies also had notable layoffs

## Tools Used
MySQL Workbench, SQL

## Files
- `layoffs_exploratory_analysis.sql` — SQL queries with comments
- `README.md` — Project documentation





















