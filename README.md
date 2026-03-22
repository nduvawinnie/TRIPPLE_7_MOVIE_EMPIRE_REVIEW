
# 🎬 TRIPPLE 7 MOVIE EMPIRE REVIEW
# TRIPPLE 7 MOVIE EMPIRE REVIEW

# **Table of Content**
#### **1. Overview**
#### **2. Business Problem**
#### **3. Business Understanding**
#### **4. Data Understanding**
#### **5. Data Cleaning and Preparation**
#### **6. Business Analysis, Key Findings, and Recommendations**
#### **7. Conclusion**
#### **8. Resources and Links**

## 1. **Overview**
Triple 7 Movie Empire is a startup company that wants to compete in the movie industry.  This analysis will help to give a general overview of the industry, to ensure the stakeholders understand how the industry works and what to expect of it, which will be ideal for decision-making.

## **Key Business Questions**
#### 1. Which movie genres are the most profitable?
#### 2. When is the best time to release a movie for maximum returns?
#### 3. Do higher-rated movies generate more revenue?

## 2. Business Problem
Tripple Seven plans to launch a new movie studio but lacks experience in the film industry. The company does not know which types of movies perform best at the box office or what factors contribute to financial success. Without proper analysis, investing in movie production could lead to financial losses. This project uses historical movie data to identify profitable trends and reduce investment risk.

## 3. Business Understanding
The movie industry is a multi-billion-dollar industry that has been growing rapidly in recent years, evolving from analog to digital eras.
#### Major growth factors include:
- Internet and Streaming Platforms: Movies are now easily accessible worldwide without needing physical stores (CDs/DVDs).
- Visual Effects (CGI, VFX): Ensures high-quality production.
- Large Investments: Secures timely production and distribution.
- Changing Audience Preferences: Diverse genres cater to a global audience.

#### Industry risks include:
piracy, budget overruns, economic downturns, weather-related issues, cast illness/injury, and poor box-office performance.

#### Mitigation Strategy:
Data analysis helps identify trends and audience preferences to reduce risk during planning and production.

#### Objectives
- Determine the most profitable movie genres.
- Identify the best time to release a movie for maximum returns.
- Analyze whether higher-rated movies generate more revenue.

## 4. Data Understanding
##### Data Source The data was sourced from GitHub: https://github.com/learn-co-curriculum/dsc-phase-2-project-v3
### 4.1 Selected Datasets 
- *tmdb.movies.csv* – movie genres, ratings, popularity, and release dates 
- *tn.movie_budgets.csv* – production budget, domestic gross, and worldwide gross
### 4.2 Selected Columns 
*tmdb.movies.csv* 
-title 
-genre_ids 
- vote_average
- popularity
- release_date
*tn.movie_budgets.csv*
- movie
- production_budget
- domestic_gross
- worldwide_gross
- release_date
### 4.3 Visualization Metrics 
- Genres
- Production Budget
- Domestic Gross
- Worldwide Gross
- Total Profit
- Vote Average
- Release Year
- Release Month

## 5. Data Cleaning 
- Merged the two datasets
- Converted budget and revenue columns to numeric values
- Removed duplicates 
-  Extracted release year and release month
- Created total profit column - Converted genre IDs into genre names
- Created a return on investment column 
- Handled missing values

## 6. Data Analysis

### 6.1 Univariate Analysis 
- Distribution of movie ratings
- Summary statistics of revenue and profit 
- Genre distribution

### 6.2 Bivariate Analysis 
- Movies produced per year 
- Genre vs total profit 
- Domestic vs worldwide gross

### 6.3 Multivariate Analysis 
-Correlation analysis 
-Relationship between ratings, revenue, and profit

##  Key Findings 
- Adventure, Animation, and Fantasy genres generate the highest profits 
- Worldwide gross strongly influences total profit 
- Higher ratings do not strongly guarantee higher revenue 
- Movie production increased significantly after 2010 
- Global markets generate higher revenue than domestic markets

##  Recommendations  
- Invest in profitable genres such as Adventure, Animation, and Fantasy 
- Release movies during peak seasons (May–July and November–December) 
- Focus on global markets to increase worldwide revenue 
- Balance production budget and commercial appeal

## 7. Conclusion
The analysis provides actionable insights for Triple 7 Movie Empire to guide production, release strategy, and budget allocation. By focusing on profitable genres, strategic release timing, and global market expansion, Tripple 7 can reduce financial risk and improve its chances of success in the movie industry.

## Resources and links
### *Tableau dashboard:*
https://public.tableau.com/views/Group7ProjectMovies/Trippe_777_Movies?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
### *Tripple_7_movie_empire:*
pdf
### *Final notebook:*
project.ipynb


