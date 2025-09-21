# Civic-Pulse-NYC-Service-Request-Analysis

The Challenge: I wanted to tackle a real-world, messy dataset to understand how a major city functions. My goal was to step into the shoes of a city official and use data to answer a critical question: What are the most pressing issues for New Yorkers, and how effectively is the city responding? This project analyzes over 750,000 public service requests from the first quarter of 2024 to find the story behind the numbers.

My approach and Tech Stack: This project was a complete end-to-end analysis. The raw data was spread across six large files, far too big for Excel, so I used Python and Pandas as my primary tools for the heavy lifting of combining and cleaning the data.

Once the data was prepared, I loaded it into an SQLite database. From there, I connected Power BI directly to the database and used SQL queries to pull the specific data needed for each visualization. This ensured the dashboard was both efficient and scalable.

What I Discovered: Parking & Housing Are Top of Mind: The data clearly showed that Illegal Parking and a lack of Heat/Hot Water were the dominant complaints. This suggests that daily quality-of-life issues and housing standards are major pain points for citizens. Two Agencies on the Front Line: A huge portion of the workload falls on two agencies: the NYPD and the Department of Housing (HPD), which together handle over 70% of all incoming requests. The Performance Metric: I found that the city takes, on average, just under one day (2.3 days) to resolve a complaint, though this varies significantly by complaint type. The Epicenters of Activity: The analysis revealed that Brooklyn and Queens are the city's hotspots, together accounting for more than half of all service requests filed.

The Final Dashboard Here is a image link of the interactive dashboard I built in Power BI to visualize these findings. Each chart is powered by a direct SQL query to the database.

image
