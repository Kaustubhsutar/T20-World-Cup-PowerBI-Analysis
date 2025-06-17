# T20-World-Cup-PowerBI-Analysis
Interactive Power BI dashboard analyzing ICC T20 World Cup stats with role-based insights, custom KPIs, and a star schema data model. Leveraging real-world cricket data to build an insightful Power BI dashboard. This project showcases data collection, transformation, modeling, and interactive visualization, focused on identifying the **Best XI players** from the ICC T20 World Cup 2022.

## 📌 Project Highlights

- 🔍 **Objective**: Analyze T20 World Cup 2022 data to identify high-impact players by role and build a data-driven "Best XI" team.
- 📊 **Toolset**: Web scraping, Python (Pandas), Power BI, Star Schema Modeling
- 📁 **End-to-End Workflow**: Data collection → preprocessing → modeling → visualization


## 🛠 Tools & Technologies Used

- **Web Scraping**: Bright Data platform + ESPNcricinfo dataset
- **Python**: Data cleaning & transformation with **Pandas**
- **Power BI**: Dashboard creation, DAX-based KPIs, custom visuals
- **Data Model**: Star Schema (Fact + Dimension tables)


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

## 📁 Files Used

The following files were used to build the Power BI data model and generate advanced insights:

### 📄 Data Sources (CSV)
- `dim_match_summary.csv` – Match-level metadata (teams, venue, date, winner)
- `dim_players.csv` – Player profiles (with images)
- `dim_players_no_images.csv` – Alternate player info without image paths
- `fact_batting_summary.csv` – Batting performance data (runs, SR, boundaries)
- `fact_bowling_summary.csv` – Bowling performance data (wickets, economy, etc.)

### 📊 DAX Measures & Calculated Columns
- `DAX Measures and Calculated columns.xlsx` – Contains the logic used for:
  - Custom KPIs (e.g., Death Overs Impact, Dot %, Finisher Rating)
  - Role-wise calculations
  - Ranking and filters for visuals

## 📌 How to Use

To explore and interact with the dashboard:

1. **Clone or download** this repository.
2. Open `t20_wc_statistics.pbix` using **Power BI Desktop** (v2023 or later).
3. Make sure the following CSV files are available in the same folder:
   - `dim_match_summary.csv`
   - `dim_players.csv`
   - `fact_batting_summary.csv`
   - `fact_bowling_summary.csv`
4. Load the `.pbix` file and check if the data loads correctly. If needed, **use Power Query to re-map the data source paths**.
5. Explore the dashboard:
   - Use slicers to filter by team, player role, venue, match, etc.
   - Hover over KPIs to view tooltips and insights.
   - Drill through player profiles to see role-specific breakdowns.




