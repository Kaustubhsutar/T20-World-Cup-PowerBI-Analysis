# T20-World-Cup-PowerBI-Analysis
Interactive Power BI dashboard analyzing ICC T20 World Cup stats with role-based insights, custom KPIs, and a star schema data model. Leveraging real-world cricket data to build an insightful Power BI dashboard. This project showcases data collection, transformation, modeling, and interactive visualization, focused on identifying the **Best XI players** from the ICC T20 World Cup 2022.

## 📌 Project Highlights

- 🔍 **Objective**: Analyze T20 World Cup 2022 data to identify high-impact players by role and build a data-driven "Best XI" team.
- 📊 **Toolset**: Web scraping, Python (Pandas), Power BI, Star Schema Modeling
- 📁 **End-to-End Workflow**: Data collection → preprocessing → modeling → visualization


## 🛠 Tools & Technologies Used

- **🕸 Web Scraping**: Bright Data platform + ESPNcricinfo dataset
- **🐍 Python**: Data cleaning & transformation with **Pandas**
- **📐 Power BI**: Dashboard creation, DAX-based KPIs, custom visuals
- **🧮 Data Model**: Star Schema (Fact + Dimension tables)


## 🚀 Key Features

### 📈 Multitude of Custom KPIs
- Batting: Strike Rate, Average, Boundary %, Dot Ball %
- Bowling: Economy, Wicket %, Dot Ball %, Match Impact Index
- Role-based stats: Aggregated KPIs by Power Hitters, Anchors, Finishers, Bowlers, All Rounders

### 🎨 Dynamic & Custom Visuals
- Role-specific icons (e.g., batsman, bowler)
- Slicers for team, match, player role filters

### 🧱 Star Schema Data Model
- Fact Table: Player-Match Statistics
- Dimension Tables: Players, Teams, Matches, Roles
- Optimized for Power BI relationships and DAX efficiency

### 🧠 Data-Driven Insights
- Auto-ranked Best XI based on KPIs
- Role distributions by team
- Most efficient players per match stage (Powerplay, Middle, Death)

## 📈 How to Use

1. Clone/download the repository.
2. Open `T20_World_Cup_Analysis.pbix` in Power BI Desktop.
3. Explore various pages and slicers.
4. View dynamic insights for player selection and team analysis.


