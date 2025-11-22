#  911 Calls Exploratory Data Analysis

## Project Overview
This project is an exploratory data analysis of real 911 emergency call records. My goal was to understand when and why most calls occur, which areas experience the highest emergency activity, and what patterns might help improve resource planning for emergency services.

Instead of jumping straight into modeling, I focused on truly understanding the data—its patterns, trends, and the story behind the numbers.

## Dataset
The dataset comes from public 911 call logs and contains tens of thousands of records. A few fields that were especially important in this analysis include:

- `timeStamp` — the exact time of each call  
- `title` — the description of the emergency  
- `zip`, `lat`, `lng`, `twp` — geographic information  
- `reason` — the emergency category (EMS, Fire, or Traffic)

## How I Approached the Analysis

### 1. Getting the Data Ready
The first step was understanding the structure of the dataset and preparing it for analysis. This included:
- Converting timestamps into proper datetime format  
- Extracting hour, day of the week, and month  
- Splitting the “title” column to identify the main emergency category  
- Checking for any missing or inconsistent values  

### 2. Exploring Patterns and Trends
Once the data was prepared, I looked at several questions:

- **When do most emergencies occur?**  
  I analyzed daily, hourly, and monthly trends to get a complete time-based view.

- **Which emergency types are most common?**  
  EMS, Fire, and Traffic calls were compared to see which categories dominate.

- **Are certain areas more likely to emergencies?**  
  Zip code and township data helped reveal geographic hotspots.

### 3. Visualizations
To better understand the patterns, I created several visualizations including:
- Line charts for hourly and daily call trends  
- Count plots for call types  
- Heatmaps showing call frequency by hour/day and day/month  

These visual summaries made it easy to identify recurrent patterns, especially peak hours and high-activity locations.

## Key Insights

- **EMS calls** were the most common type in the dataset.  
- There were clear **peak hours**, typically in the late afternoon and early evening.  
- Some locations consistently showed higher emergency activity than others.  
- Time-based heatmaps revealed very steady and predictable call patterns.

## Tools Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Author
**Jameela Al-Smadi**  
 jameelasmadi98@gmail.com


