# Exploring Road Safety: A Deep Dive into the US Accidents Dataset

## 📊 Project Overview

This project presents a comprehensive analysis of the US Accidents dataset, exploring patterns, trends, and insights related to traffic accidents across the United States. The analysis covers a 6-year period and provides valuable insights into road safety factors, temporal patterns, and geographical distributions.

## 🎯 Key Objectives

- Analyze accident patterns across different time periods and locations
- Identify high-risk areas and contributing factors
- Explore temporal trends in accident occurrences
- Understand the relationship between various traffic features and accident frequency
- Provide actionable insights for road safety improvements

## 📈 Dataset Information

**Source**: [US Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) by Sobhan Moosavi  
**Time Period**: 6 years of accident data  
**Features**: 46 variables including location, weather, traffic conditions, and accident details  
**Size**: Comprehensive dataset with 7million+ of accident records

## 🔍 Analysis Methodology

### Data Exploration
- **Data Profiling**: Comprehensive analysis using pandas-profiling for initial data understanding
- **Missing Value Analysis**: Identification and handling of missing data
- **Correlation Analysis**: Exploration of relationships between variables
- **Statistical Analysis**: Distribution analysis and summary statistics

### Visualization Techniques
- **Geographical Analysis**: Mapping accident hotspots and regional patterns
- **Temporal Analysis**: Time-based visualizations for accident trends
- **Statistical Plots**: Histograms, distribution plots, and correlation heatmaps
- **Interactive Visualizations**: Dynamic charts for better data exploration
- **Correlation Analysis**: Heatmaps showing relationships between features
- **Time Series Analysis**: Hourly and daily accident pattern visualizations

## 📊 Key Findings

### 🏙️ Geographical Distribution
- **High-Risk Cities**: Less than 4.5% of cities (494 cities) had more than 1,000 accidents
- **Low-Risk Areas**: More than 4,400 cities had less than 10 accidents over the 6-year period
- **Regional Patterns**: Accidents were more frequent in coastal areas, with central regions showing lower accident rates
- **Notable Absence**: New York City data was not present in the dataset

### ⏰ Temporal Patterns

#### Weekday Accidents
- **Peak Hours**: Most accidents occurred during 6 AM to 9 AM and 3 PM to 6 PM
- **Commute Correlation**: Peak times align with typical office and home commute periods
- **Pattern**: Clear bimodal distribution reflecting rush hour traffic

#### Weekend Accidents
- **Different Pattern**: Bell curve distribution with peak between 10 AM to 3 PM
- **Leisure Time**: Accidents concentrated during typical leisure and shopping hours
- **Opposite Trend**: Weekend patterns differ significantly from weekday patterns

### 📈 Visual Analysis

#### Accident Patterns by Hour
![Accident Patterns by Hour](Accident_by_hours.png)

*This visualization shows the distribution of accidents across different hours of the day, revealing clear patterns in accident timing. The analysis demonstrates distinct peaks during rush hour periods and different patterns for weekdays versus weekends.*

#### Feature Correlations
![Correlations Between Features](Correlations_between_col.png)

*This correlation heatmap reveals the relationships between different traffic and environmental features in the dataset. It helps identify which factors are most strongly associated with accident occurrences and provides insights for predictive modeling.*

#### Accident Distribution by State
![US Accidents by State](us_accident_by_state.png)

*This visualization shows the geographical distribution of accidents across different US states, highlighting regional variations in accident frequency and identifying high-risk areas that require targeted safety interventions.*

### 🚦 Traffic Features Analysis
- **Traffic Signals**: Strong correlation with accident frequency
- **Traffic Calming**: High correlation with accident occurrences
- **Weather Conditions**: Temperature and wind chill show significant correlations
- **Road Features**: Various road infrastructure elements impact accident rates

### 📈 Statistical Insights
- **Data Quality**: Comprehensive dataset with 46 variables for detailed analysis
- **Correlation Patterns**: Multiple high correlations identified between traffic features
- **Imbalanced Data**: Some features show significant imbalances requiring careful interpretation
- **Missing Data**: Strategic handling of missing values for robust analysis

---

*This analysis provides valuable insights into road safety patterns and can inform policy decisions, infrastructure improvements, and public safety initiatives across the United States.* 