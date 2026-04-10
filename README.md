
# Project Overview
This project performs a comprehensive data analysis on a Swiggy Dataset using SQL. The goal is to extract actionable business insights regarding restaurant performance, consumer spending habits, and regional revenue distribution. By analyzing various metrics like ratings, order volume, and pricing segments, this project demonstrates how data-driven decisions can optimize food delivery operations.

# Dataset Information
The dataset contains detailed information about Swiggy’s operations, including:

City & Location: Geographical data of orders.

Dish Details: Names and pricing of various food items.

Ratings: Customer feedback (Rating and Rating Count).

Order Metadata: Specific dates and timestamps for trend analysis.

# Tech Stack
Language: SQL (Structured Query Language)

Database Management System: SQL Server / PostgreSQL

Analysis Focus: Data Cleaning, Aggregations, Window Functions, and CTEs.

# Key Business Questions Addressed
In this project, I solved 12 specific business problems:

Market Presence: Identified all unique cities where Swiggy operates.

Premium Catalog: Filtered high-value dishes priced above 500 INR.

Revenue Analysis: Calculated total revenue generated per city, ranked from highest to lowest.

Quality Metrics: Analyzed average ratings for food categories (e.g., North Indian, Chinese).

Logistics Planning: Identified top 5 locations with the highest order density.

Pricing Strategy: Categorized dishes into 'Budget', 'Mid-range', and 'Premium' segments.

Regional Favorites: Found the most expensive dish and its price for every city.

Hidden Gems: Identified restaurants with high ratings (>4.5) but low order counts.

Time-Series Trends: Analyzed monthly order volume growth.

Market Share: Calculated the percentage contribution of each city to total revenue.

Performance Issues: Flagged restaurants with high traffic but poor customer ratings.

Operational Peaks: Determined the busiest day of the week using date functions.
