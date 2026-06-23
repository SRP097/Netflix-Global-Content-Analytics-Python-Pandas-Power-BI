# Netflix Global Content Analytics

## Project Overview

This project focuses on analyzing Netflix's global content catalogue using Python (Pandas) and Power BI. The objective is to transform raw Netflix data into meaningful business insights through data cleaning, preprocessing, exploratory data analysis (EDA), and interactive dashboard development.

The analysis explores content distribution across countries, genres, audience ratings, and release years while identifying growth patterns in Netflix's content library over time.

---

## Project Objectives

- Clean and preprocess raw Netflix data.
- Analyze the distribution of Movies and TV Shows.
- Identify content growth trends over time.
- Evaluate country-wise content production.
- Examine genre popularity and distribution.
- Analyze audience segmentation using content ratings.
- Develop interactive Power BI dashboards.
- Generate business recommendations based on analytical findings.

---

## Dataset Information

| Attribute | Details |
|------------|----------|
| Dataset Name | Netflix_Database.csv |
| Records | 8,804 |
| Columns | 12 |
| Format | CSV |
| Tools Used | Python (Pandas), Google Colab, Power BI |

### Dataset Columns

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

---

## Technologies Used

### Data Processing
- Python
- Pandas
- NumPy
- Google Colab

### Data Visualization
- Microsoft Power BI

### Documentation
- Microsoft Excel
- Microsoft PowerPoint

---

## Data Preparation

The dataset underwent multiple preprocessing steps:

- Missing value handling
- Data type correction
- Column standardization
- Date transformation
- Dataset restructuring
- Creation of additional analytical datasets

### Derived Datasets

#### country_df
Created by splitting and exploding the country column to support country-wise analysis.

#### genre_df
Created by splitting and exploding the listed_in column to support genre-wise analysis.

---

## Key Performance Indicators (KPIs)

The dashboard summarizes Netflix's content catalogue through:

- Total Titles
- Total Movies
- Total TV Shows
- Total Countries
- Total Genres

### KPI Results

| KPI | Value |
|-------|--------|
| Total Titles | 8,804 |
| Total Movies | 6,128 |
| Total TV Shows | 2,676 |
| Total Countries | 124 |
| Total Genres | 42 |

---

## Analysis Performed

### 1. Country-wise Content Distribution

Analyzed Netflix content availability across different countries.

#### Key Insights
- United States is the largest content contributor.
- India is the leading contributor in Asia.
- Netflix maintains a globally diversified content portfolio.
- Content contribution follows a long-tail distribution pattern.

---

### 2. Genre Popularity Analysis

Analyzed the popularity and distribution of genres.

#### Key Insights
- International Movies are the most popular genre.
- Dramas and Comedies have strong representation.
- Movies dominate most genre categories.
- Netflix maintains a highly diversified content library.

---

### 3. Audience Segmentation Analysis

Analyzed content ratings to understand target audiences.

#### Key Insights
- TV-MA is the most common rating category.
- Netflix primarily targets mature and teenage audiences.
- Family-oriented content exists but represents a smaller share.
- Movies dominate across most rating categories.

---

### 4. Content Growth Analysis

Analyzed annual content additions and expansion trends.

#### Key Insights
- Significant growth started after 2015.
- Peak content additions occurred in 2019.
- Movies consistently outnumber TV Shows.
- Netflix experienced rapid expansion between 2017 and 2020.

---

## Power BI Dashboard

The project includes a 5-page interactive Power BI dashboard.

### Dashboard Pages

### 1. Netflix Overview
- KPI Cards
- Movie vs TV Show Distribution
- Year-wise Content Growth
- Interactive Filters

### 2. Country Overview
- Global Content Map
- Top 10 Countries by Content Count
- Country-wise Movie vs TV Show Comparison

### 3. Genre Overview
- Top 10 Genres
- Genre Distribution Treemap
- Genre-wise Content Type Analysis

### 4. Audience Rating Overview
- Rating Distribution Donut Chart
- Top Rating Categories
- Content Type by Rating Analysis

### 5. Yearly Trend Overview
- Content Growth Trend
- Release Year Distribution
- Release Year vs Added Year Scatter Plot

---

## Repository Structure

```text
Netflix_Global_Content_Analytics/
│
├── Data/
│   ├── Netflix_Database.csv
│   ├── country_df.xlsx
│   └── genre_df.xlsx
│
├── PowerBI/
│   └── Netflix_Global_Content_Analytics_Dashboard.pbix
│
├── Reports/
│   └── Netflix_Global_Content_Analytics_Project_Report.pdf
│
├── Presentation/
│   └── Netflix_Global_Content_Analytics_Presentation.pdf
│
└── README.md
```

---

## Business Recommendations

### Global Diversification
Continue investing in localized content for emerging markets.

### Movie-Heavy Catalogue
Increase investment in high-quality TV series to improve audience retention.

### Growing International Focus
Expand multilingual content production and international partnerships.

### Strong Mature Audience Segment
Increase family-friendly and youth-oriented content offerings.

### Sustainable Growth
Balance content quantity with quality while leveraging predictive analytics for future planning.

---

## Future Scope

- Viewer engagement analysis
- Subscription growth analysis
- Content recommendation modeling
- Predictive analytics and forecasting
- Sentiment analysis using viewer reviews
- Machine Learning-based content trend prediction



**Smruti Ranjan Pradhan**

Netflix Global Content Analytics Project using Python (Pandas) and Power BI.
