<h1 style="font-size: 36px;">EDA on Ultra Marathon Dataset (1798 - 2019)</h1>


---

## **Table of Contents**
1. [Executive Summary](#executive-summary)
2. [Project Goals](#project-goals)
3. [Data Sources](#data-sources)
4. [Steps Performed](#steps-performed)
5. [Key Insights](#key-insights)
6. [Visualizations and Results](#visualizations-and-results)
7. [Quantitative Highlights](#quantitative-highlights)
8. [Next Steps](#next-steps)

---

## **Executive Summary**
This project analyzes ultra-marathon race data from 2019 to uncover trends in participant demographics, performance, and event characteristics. Insights focus on race distances, athlete performance, and gender-specific trends based on USA races in 2019.

---

## **Project Goals**
- Clean and preprocess a large historical dataset of ultra-marathon events.
- Explore gender differences in participation and performance.
- Identify top-performing athletes and races based on speed and completion time.
- Analyze seasonal trends and how event distances influence athlete outcomes.
- Provide actionable insights to organizers, participants, and enthusiasts.

---

## **Data Sources**
- Dataset size: **7,461,195 records** with 13 features.
- Focused on USA races from 2019, filtering to standardized distances: **50km, 50mi, 100km, and 100mi**.

---

## **Steps Performed**
1. **Data Cleaning:**
   - Filtered for USA races and selected standard distances.
   - Addressed missing values and corrected data types.

2. **Data Transformation:**
   - Extracted useful fields like athlete age and country.
   - Converted performance times into numeric formats.

3. **Visualization and Statistical Analysis:**
   - Explored demographic trends, gender comparisons, and seasonal participation.
   - Analyzed top-performing events and athletes.

---

## **Key Insights**
1. **Demographics:**
   - Male athletes dominate participation, especially in longer races.
   - Average participant age: **41 years**.

2. **Performance Highlights:**
   - Fastest 50km finish time: **2.83 hours**.
   - Best-performing event: ***Caumsett Park 50K Championships***.

3. **Race Trends:**
   - **50km and 50mi** races are the most popular.
   - **Spring and Summer seasons** see the highest participation.

4. **Gender-Specific Insights:**
   - Men are faster than women across all distances.
   - Women exhibit more consistent speed in races.

---

## **Visualizations and Results**

### Suggested Visualizations:
1. **Participation by Gender Across Distances:**  
   A bar chart showing the number of male and female participants in 50km, 50mi, 100km, and 100mi races.  
   ![image](https://github.com/user-attachments/assets/6de66af0-e011-4792-b000-b1ee2f8fbb20)


2. **Age Distribution of Athletes:**  
   A histogram showing the distribution of athletes’ ages, highlighting the concentration around 30-50 years.  
   ![image](https://github.com/user-attachments/assets/0a675a44-d4ec-41a0-841a-9802f923b9c6)


3. **Average Speed by Gender and Distance:**  
   A grouped bar chart comparing average speeds of male and female athletes across distances.  
   ![image](https://github.com/user-attachments/assets/d3a3b1f3-58d9-4718-a8f7-f49d65ddbbcd)


4. **Seasonal Participation:**  
   A pie chart displaying the percentage of races held in each season (spring, summer, fall, winter).  
   ![image](https://github.com/user-attachments/assets/d21658eb-1efc-486d-a2e5-ea29dccb2e4a)

5. **Top 5 Events with Fastest Finish Times:**  
   A horizontal bar chart listing events with the fastest average completion times.  
   ![image](https://github.com/user-attachments/assets/946065b0-ae7c-4c58-9ec5-9df996b4e070)


---

## **Quantitative Highlights**
- Total records in dataset: **7,461,195**.
- Filtered dataset size: **88,064** (USA events, 2019).
- Fastest 50km time: **2.83 hours**.
- Longest event time: **120 hours** (*Across the Years* event).
- Popular event: ***AZT Oracle Rumble 50km* with 159 participants**.

---

## **Next Steps**
1. Extend analysis to multi-year trends for other regions.
2. Build predictive models for performance based on historical data.
3. Create dynamic dashboards to track trends in real time.

---
