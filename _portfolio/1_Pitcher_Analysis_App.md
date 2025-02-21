---
title: "Pitcher Analysis App"
excerpt: "An interactive app that lets you pick any MLB pitcher and visualize their pitch tendencies, location patterns under specific scenarios, progression metrics, and percentile rankings.<br/><img src='/images/Strikezone_Count.png'>"
collection: portfolio
---

## Pitcher Analysis App
(Make sure to select a Pitch Type in order to see the strikezone visualization) 

<iframe src="https://nolanlo.shinyapps.io/Pitcher_Analysis_App/" width="100%" height="800" style="max-width: 1200px; margin: 0 auto; display: block;" frameborder="0"></iframe>
The embedding of the Shiny app above may distort some of the visualizations. Alternatively, [click here to open the Pitcher Analysis App in your own browser tab](https://nolanlo.shinyapps.io/Pitcher_Analysis_App/).

---

## Explanation of the App

The **Pitcher Analysis App** is an interactive tool designed for in-depth analysis of MLB pitchers. The app provides a comprehensive breakdown of pitch tendencies, performance trends, and percentile rankings across several categories. Below is an overview of each tab included in the app:

---

### **1. Pitch Breakdown**
In the **Pitch Breakdown** tab, you can explore how a pitcher performs under specific scenarios. The user can:
- **Filter by pitch result** (e.g., strikeout, hit, home run) or by **count** (e.g., 0-2, 3-0).
- View the **location of pitches** in the strike zone and plate visualizations, with colored dots representing different pitch types.
- Differentiate between pitches thrown to left- vs. right-handed batters.
- Specify a date range to focus on recent or historical trends.
- A table below the visualizations shows the **proportion of pitch types thrown** in each scenario.

This tab is great for identifying a pitcher’s preferences and tendencies in specific scenarios.

![Pitch Breakdown Visualization](/images/Strikezone_Count.png)

---

### **2. Release/Movement**
The **Release/Movement** tab provides a detailed analysis of the pitcher's release points and pitch movement profiles:
- **Release Point Visualization**: Displays where the pitcher releases each pitch, with colors differentiating between pitch types.
- **Movement Profile**: Visualizes how each pitch type moves, offering insights into the horizontal and vertical break.

These visualizations help to understand how a pitcher’s mechanics and pitch movement contribute to their effectiveness.

![Release and Movement Visualization](/images/Movement_Matrix.png)

---

### **3. Velo/Arsenal Progression**
The **Velo/Arsenal Progression** tab tracks a pitcher’s velocity and pitch arsenal trends over time using three key graphs:
1. **Velocity by Inning**: Highlights whether the pitcher’s velocity increases or decreases as the game progresses.
2. **Velocity by Game Date**: A time-series graph showing how pitch velocities evolved throughout the season.
3. **Pitch Type Proportions by Game Date**: Shows how often each pitch type was thrown game by game, highlighting consistency or changes in the pitcher’s arsenal.

These graphs offer valuable insights into a pitcher’s endurance, seasonal trends, and pitch selection strategies.

![Velo and Arsenal Progression Visualization](/images/Velocity_Graph.png)

---

### **4. Percentile Rankings**
The **Percentile Rankings** tab allows you to compare a pitcher’s metrics to other MLB pitchers who pitched at least 100 innings during the 2024 season. Key features include:
- Rankings for basic metrics such as **WHIP** and **FIP**.
- Split metrics for performance against left- vs. right-handed batters, including **K%** and **xWOBA**.
- Pitch-specific rankings, comparing a specific pitch (e.g., slider) against the same pitch type from other pitchers for metrics like:
  - Velocity
  - Spin rate
  - Whiff rate
  - xWOBA

This tab provides a comprehensive overview of how a pitcher stacks up against their peers.

![Percentile Rankings Visualization](/images/Stats_Rankings1.png)
![Percentile Rankings Visualization](/images/Stats_Rankings2.png)
![Percentile Rankings Visualization](/images/Pitch_Rankings.png)
