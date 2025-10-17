# Data Jobs Dashboard

## 📊 Dashboard Overview

This Power BI dashboard provides insights into the data jobs market, analyzing salary trends, job distribution, and employment characteristics across various data-related roles. The dashboard consists of two main pages: an overview page and a drill-through detail page for individual job titles.

## 🎯 Purpose

This dashboard enables users to:
- Track overall data job market metrics and trends
- Compare salaries across different data roles
- Identify the highest-paying positions in the data field
- Analyze job posting trends throughout 2024
- Drill through to specific job titles for detailed analysis
- Understand geographic distribution and job characteristics

## 📈 Dashboard Structure

### Page 1: Main Overview

**Key Metrics (Top Cards)**
- **Job Count**: Total number of data jobs analyzed (479K)
- **Median Yearly Salary**: Overall median annual compensation
- **Median Hourly Salary**: $47.62 median hourly rate
- **Salary Star Rating**: Visual rating indicator

**Visualizations**

1. **What Is The Trend Of Jobs In 2024**
   - Line chart tracking job posting volumes over time
   - Shows fluctuations throughout the year
   - Helps identify hiring patterns and seasonal trends

2. **What Is The Highest Paying Job In Data**
   - Horizontal bar chart comparing median yearly salaries by role
   - Top roles include: Senior Data Scientist, Machine Learning Engineer, Senior Data Engineer
   - Salary range displayed from $0K to $200K+

3. **Yearly Vs Hourly Median Salary by Job Title**
   - Scatter plot showing relationship between annual and hourly compensation
   - Each bubble represents a different job title
   - Helps understand salary structures across roles

4. **Job Summary Table**
   - Detailed table with columns:
     - Job Title
     - Number of Jobs
     - Median Yearly Salary ($USD)
     - Median Hourly Salary
   - Covers 9 major data roles from Business Analyst to Senior Data Scientist
   - Interactive table with conditional formatting (blue bars for Number of Jobs)

### Page 2: Job Title Drill-Through (Example: Data Engineer)

**Salary Metrics**
- **Yearly Salary Gauge**: Shows median ($126K) with min/max range
- **Hourly Salary Gauge**: Shows median ($59.16) with min/max range

**Job Characteristics (Donut Charts)**
- **Jobs With WFH**: Remote work availability (15% offer remote work)
- **Degree Mention**: Educational requirements (47% mention degree)
- **Jobs With Health Insurance**: Benefits offering (10% include health insurance)

**Market Analysis**

1. **Where Are Data Jobs In The World**
   - Interactive map visualization using bubble markers
   - Shows global distribution of data jobs
   - Larger bubbles indicate higher job concentrations
   - Covers North America, Europe, Asia, and Africa regions

2. **Which Platform Has The Most Jobs**
   - Horizontal bar chart of job posting platforms
   - LinkedIn dominates as the primary platform
   - Also tracks Indeed, BeBee, ZipRecruiter, and other job boards

3. **What Are The Types Of Data Jobs**
   - Treemap visualization showing employment types
   - Full-time positions: 89%
   - Contract positions: 9%
   - Other employment types make up the remainder

## 💾 Data Sources

- **Primary Source**: Aggregated data jobs dataset
- **Data Fields**: Job titles, salaries, locations, platforms, work arrangements, benefits
- **Time Period**: 2024 data with historical trends

## 🚀 How to Use

### Basic Navigation
1. Open the dashboard in Power BI Desktop
2. Use the **Job Title** dropdown filter to focus on specific roles
3. Click on any visualization to cross-filter other charts
4. View the summary table for quick comparisons across all roles

### Drill-Through Feature
1. Right-click on any job title in the charts or table
2. Select **Drill Through → To Job** (or click the "Drill Through To Job" button after selecting a job)
3. View detailed analysis for that specific role
4. Use the back arrow (top-left) to return to the overview page

### Interactive Filters
- **Job Title Filter**: Apply at the top to filter all visualizations
- **Cross-filtering**: Click on any chart element to filter related data
- **Table Selection**: Click rows in the table to highlight that role across all visuals

## 🔍 Key Insights

This dashboard answers questions like:
- What are the most common data job titles and their frequencies?
- Which data roles offer the highest compensation?
- How have data job postings trended throughout 2024?
- What percentage of data jobs offer remote work options?
- Where are data jobs concentrated geographically?
- Which job platforms have the most data job listings?
- How do yearly and hourly salaries compare across roles?
- What proportion of jobs require degrees or offer health insurance?

## ⚙️ Technical Details

- **Visualizations Used**: 
  - Card visuals for KPIs
  - Line chart for time series
  - Bar charts for comparisons
  - Scatter plot for correlation analysis
  - Table with conditional formatting
  - Gauge charts for salary ranges
  - Donut charts for percentages
  - Map visual for geographic data
  - Treemap for proportional data
  
- **Interactivity**: 
  - Drill-through functionality
  - Cross-filtering between visuals
  - Slicers for job title filtering
  
- **Data Modeling**: Basic Power BI relationships without custom DAX measures

## 📝 Notes

- All salary figures are in USD
- The dashboard uses built-in Power BI aggregations (sum, median, count)
- Drill-through page dynamically updates based on selected job title
- Map visualization requires location data to be properly geocoded

---

**Navigation Tip**: Use the drill-through feature to explore detailed insights for any specific data job role!