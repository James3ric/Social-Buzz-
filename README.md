# Social-Buzz

# Social Buzz: Content Popularity Analysis

## Project Overview
This repository contains the solution for the Social Buzz project, which focuses on analyzing content categories to identify the top 5 categories with the largest aggregate popularity. The project is part of a 3-month engagement designed to showcase our expertise and help Social Buzz prepare for their upcoming IPO.

## Client Background  

Social Buzz is a rapidly growing social media platform emphasizing content-centric feeds and unique user reactions. With over 100 reaction types and unstructured data generated from 100,000 daily posts, the company requires sophisticated data management solutions and strategic guidance for scaling and IPO readiness.

## Project Objectives
1. Conduct an **audit of Social Buzz's big data practice** to identify strengths, weaknesses, and opportunities for improvement.
2. Provide **recommendations for a successful IPO** based on best practices and insights from previous IPO engagements.
3. Perform an **analysis of content categories**, identifying the top 5 categories with the highest aggregate popularity scores.

## Deliverables
1. A clean and merged dataset containing:
   - Content ID
   - Category
   - Content Type
   - Reaction Type
   - Reaction Score
2. Analysis of the top 5 performing content categories based on total popularity scores.
3. Visualizations and insights into category performance.

## Process and Methodology

### 1. Data Preparation
The analysis involved merging three datasets:
- **Reaction Table**: Base table containing reaction-related data.
- **Content Data**: Provides details about content ID, category, and type.
- **Reaction Types Data**: Contains reaction type descriptions and corresponding scores.

#### Steps:
- **Merge Data**: Used the Reaction table as the base and joined it with Content and Reaction Types data. A `VLOOKUP` function in Excel facilitated this process.
- **Clean Data**: Removed duplicates, handled missing values, and ensured consistency in columns.
- **Aggregate Scores**: Calculated the total scores for each category using the `SUMIF` function.

### 2. Top 5 Categories
- Added up the total scores for each category to determine popularity.
- Identified the top 5 categories based on their aggregate scores.

### 3. Deliverable Preparation
- **Cleaned Dataset**: Final merged and cleaned dataset uploaded to the repository.
- **Visualizations**: Charts and graphs to illustrate category performance.
- **Insights Report**: Detailed findings on the top 5 categories.

## Tools and Technologies
- **Excel**: Data merging, cleaning, aggregation, and visualization.

## Results
- A cleaned dataset containing all relevant columns.
- A ranked list of the top 5 content categories based on total scores.
- Visualizations highlighting trends and category performance.

