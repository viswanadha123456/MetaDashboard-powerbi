# MetaDashboard-powerbi
I developed a MetaDashboard in Power BI to analyze people performance and timings. It includes key KPIs such as total users,Impressions, top members, and customer insights. The dashboard helps in tracking performance and making data-driven decisions.
<a href:https://github.com/viswanadha123456/MetaDashboard-powerbi>

Business Requirements Document (BRD)

Meta Ad Performance Analysis Report

1.Business Objective
The organization needs a unified performance-tracking report for advertising campaigns running on Facebook and Instagram.
The report will provide visibility into reach, engagement, conversions, and budget utilization, enabling the marketing team to:
Identify the most effective platform (Facebook vs Instagram).
Track campaign ROI and optimize budget allocation.
Understand audience engagement patterns across demographics and geographies.
2. Scope
In Scope
Paid advertising campaigns on:
Facebook
Instagram
Out of Scope
Other Meta platforms (Messenger, Audience Network)
Organic (unpaid) engagement
Third-party or offline marketing channels

KPIs List    
Primary KPIs
Impressions
Clicks
Shares
Comments
Purchases



Derived KPIs
Engagements
CTR (Click Through Rate)
Engagement Rate
Conversion Rate
Purchase Rate
Total Budget
Avg Budget per Campaign

Charts Requirements: 
1. Target Gender – Donut Chart 
A donut chart will visualize performance split by target gender (from the ads table). 
• The metric displayed (e.g., Impressions, Clicks, Purchases) will change dynamically via 
the parameter. 
• Purpose: Identify which gender segment contributes most to the selected metric. 

2. Target Age Group – Bar Chart 
A bar chart will show engagement across age groups defined in the ads table. 
• Each bar will represent one age group. 
• The metric displayed will switch dynamically. 
• Purpose: Highlight which age group is most responsive to campaigns. 

3. Country – Map 
A map visualization will display performance by country (from the users table). 
• Bubble size or color intensity will represent the selected metric. 
• Purpose: Provide a geographic view of campaign reach and engagement. 

4. Calendar Month – Calendar Heat Map 
A calendar heat map will plot performance at the monthly level, based on the timestamp 
field in ad_events. 
• Darker shades will indicate higher activity. 
• Purpose: Detect seasonal trends, peak ad months, and low-activity periods. 

5. Weekly Trend – Stacked Column by Ad Type 
A stacked column chart will display weekly performance trends. 
• X-axis → Week number (from the Date Table linked to ad_events). 
• Stacks → Different ad_type values (from the ads table). 
• Y-axis → Selected metric. 
• Purpose: Compare ad type contributions over weeks.

6. Hourly Trend – Area Chart 
An area chart will show activity by hour of day (from ad_events[time_of_day]). 
• X-axis → Hour of the day (0–23). 
• Y-axis → Selected metric. 
• Purpose: Understand user activity patterns throughout the day. 

7. Ad Type – Matrix 
A matrix visualization will show the selected metric across ad types and possibly break 
down further by platform (Facebook vs Instagram). 
• Rows → Ad Types. 
• Columns → Platforms or other campaign dimensions. 
• Values → Selected metric. 
• Purpose: Compare performance across ad formats and platforms side by side.
Processes 1.Validated the data to ensure accuracy, correct calculations, and proper relationships.
2.Optimized performance by removing unnecessary columns, reducing visuals, and improving DAX measures.
3.Tested all filters and slicers to ensure smooth user interaction.
4.Collected feedback from users or stakeholders and made improvements.
5.Published the dashboard to Power BI Service and set up scheduled refresh.
6.Documented insights and prepared a short report explaining key findings and metrics.

<img width="736" height="382" alt="dashboard image" src="https://github.com/user-attachments/assets/668fa775-7574-4237-8e82-7b5eb2105992" />





