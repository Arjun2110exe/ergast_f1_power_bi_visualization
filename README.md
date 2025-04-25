# ergast_f1_visualization

![image](https://github.com/user-attachments/assets/79cd8d1e-187a-4fb1-9557-f3574caeadc0)

![image](https://github.com/user-attachments/assets/abf929bb-fd43-44bd-a474-38ac62bb322b)





# The Data Behind the Helmet

This project presents a comprehensive and interactive Power BI dashboard built using cleaned and merged data from the Ergast Developer Dataset, covering Formula 1 seasons from 1994 to 2024.

The goal was to build an immersive and data-driven experience that allows users to explore driver careers, constructor performance, team contributions, and seasonal performance trends across 30 years of F1 history.

# 🔧 Data Preparation & Cleaning:
The dataset was obtained from the Ergast Developer API and included multiple CSV files across entities such as races, qualifying, constructors, and results. We conducted a focused data-cleaning phase to optimize for analysis and performance:

- Filtered essential attributes from each file (e.g., raceId, driverId, constructorId, qualifying times, race results, status, points).

- Removed unused columns and normalized categorical fields.

- Merged datasets into a single master file using Power Query, joining:

  - Race results with race metadata (location, year)

  - Driver information with constructor details

  - Qualifying performance with final results

- Resulted in a clean, analysis-ready CSV for efficient Power BI integration.

# 📊 Dashboard Features:
🔹 Driver & Constructor Career Overview:
- Summary of debut year, nationality, wins, podiums, and total points.

- Dynamic constructor-colored visuals.

- Conditional cards showing First and Last Races, styled with team colors based on row-specific logic.

🔹 Points by Season (1994–2024):
- Yearly performance chart, color-coded by constructor.

- Interactive tooltips displaying constructor, points, and race context.

- Automatically highlights peak performance years.

🔹 Constructor Contribution Breakdown:
- Shows how many points each driver contributed to each team they drove for.

- Highlights dominant stints vs minor team appearances.

🔹 Slicer Interactivity:
- Year slicer dynamically updates visuals (e.g., constructor name/color defaulting to most recent in that year).

- Constructor hover behavior enables exploratory insights per team.

- Tooltip-rich environment enhances user experience.

# ⚙️ Technical Highlights:
- Built entirely in Power BI with DAX measures for:

  - Dynamic constructor color logic

  - Hover-based first/last race context

  - Conditional background formatting

- Used Power Query M language for transformations and joins.

- Optimized performance with star schema logic and minimized table joins.

# 🎯 Outcome:
This dashboard offers a powerful platform to:

- Explore the career of any driver and performance of constructors from 1994–2024

- Analyze their seasonal progression, team transitions, and peak performances

- Compare team contributions across time in a highly visual and intuitive way

