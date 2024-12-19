# Google-Data-Analytics-Case-Study: How Does A Bike-Share Navigate Speedy Success (With R and Tableau)

After completing the Google Data Analytics Certification course, I am now ready to tackle a case study provided by Google. I will use real-world data to perform a task as a junior data analyst for a fictional company, Cyclistic. The case study involves the company's data on its customers' trip details over a 12-month period (Jan 2022 – Dec 2022). I will follow Google’s six steps of the Data Analysis Process: Ask, Prepare, Process, Analyze, Share, and Act. For this project, I will use R and Tableau for my analysis.

## Background of the case study

### About the company

Cyclists is a fictional bike-sharing company in Chicago. It offers more than 5,800 bicycles and 600 docking stations throughout the city.

Cyclistic offers flexible pricing plans, including single-ride passes, full-day passes, and annual memberships. Casual riders, who purchase single-ride or full-day passes, makeup one segment, while Cyclistic members are those who have purchased annual memberships. Financial analysis indicates that annual members are more profitable than casual riders, leading Cyclistic to prioritize converting casual riders into members for future growth.

The director of the marketing team and manager, Lily Moreno, believes that maximizing the number of annual members will be key to future growth.

### Scenario

As a junior data analyst on Moreno's team, I was tasked with digging into the company’s historical bike trips to identify trends and help design marketing strategies to convert casual riders into annual members.

# Step 1: Ask Phase

## Business Task

Design marketing strategies aimed at converting casual riders into annual members.

## Business Questions

-   How do annual members and casual riders use Cyclistic bikes differently?
-   Why would casual riders buy Cyclistic annual memberships?
-   How can Cyclistic use digital media to influence casual riders to become members?

As a junior data analyst at Cyclistic, I have been tasked with the first objective: How do annual members and casual riders differ?

## Key Stakeholders

1.  Lily Moreno — Director of the marketing team and my manager.
2.  Cyclistic executive team
3.  Cyclistic marketing analytics team

# Step 2: Prepare Phase

## Data Location

The data is provided by Motivate International Inc. has made this data available under this license. There are 12 monthly CSV files. I will use the historical data trips from January 2022 to December 2022. After downloading the datasets from the designated website, I will organize them (.csv format) into a dedicated folder named “Cyclistic_data”

## Bias and Credibility

### ROCCC check

-   Reliable? Yes. The data is from a reliable public data source.

-   Original? Yes. It is fictitious data that is to be used for case studies.

-   Comprehensive? Yes, the data is continuously updated monthly. I will focus on data for the 12 months of 2022.

-   Current? Yes. The data files are current.

-   Cited? Yes. The data is from Motivate, and there is a license agreement.

So, yes, the data ROCCCs.

### Licensing, Privacy, Security, Accessibility

-   Licensing: The license agreement is available online.

-   Security: Data security issues are stated in the license agreement under Prohibited Conduct.

-   Accessibility: The data is accessible online for download at Amazonws.com.

## Data Integrity:

The files have been downloaded and populated. I checked the file properties of all the files to check for byte size. All the files have the same number of columns and the same names. Problems include missing data and zero values. The missing data is predominantly station names and station IDs. Omitting the columns won’t impact the case study.

-   Completeness: there are missing values in several columns.

-   Accuracy: aside from the missing data, the data is accurate.

-   Consistency: aside from the missing values, the data is consistent.

-   Timeliness: the data is always available, so it is timely.

-   Compliance: This is a nonissue as it is a case problem.

## Organize and Protect Data

Each of the 12 data files will be saved with a new name, which preserves the original files. The new files, working files, will be used for analysis. I will then back up the original and working files.

# STEP 3: Process Phase

For this analysis, I will work with the January to December 2022 data. I will be using R programming language and Tableau for my analysis and visualizations.








# Step 5: Share Phase

I used Tableau for this phase to create visualizations.

## Members vs casual riders (average ride length)

![***Fig. 1***](Fig. 1.png)

The average ride length for members is 743.5 and 1309.8 for casual riders, as shown in fig.1 above. This shows that casual riders had the longest rides compared to member riders.

## Average Ride Length by Bike Type

![***Fig. 2***](Fig. 2.png)

As shown by figure 2, on average, casual riders who used docked bikes had the longest rides whereas annual members did not use the docked bikes at all.

## Average Ride Length by Day of the Week

![***Fig. 3***](Fig. 3.png)

On average, casual riders ride bikes for longer periods every day of the week compared to riders with annual memberships as shown in figure 3 above. Weekends have the longest travelled distance by both casual riders and annual members.

## Average Ride Length by Bike Type by Day of the Week

![***Fig. 4***](Fig. 4.png)

From Fig. 4 above the average ride length for all bike types was on weekends for both casual riders and annual members. For docked bikes, the highest average ride length for casual riders was on Sunday.

# Step 6: Act Phase

# Recommendations

### Key Summaries

1.  Total Number of Rides

    The data reveals significant differences in usage patterns between casual riders and members, indicating that casual riders constitute a substantial portion of total rides.

2.  Average Ride Length

    Casual riders exhibit longer average ride durations compared to members. Specifically, the average ride length for casual riders was 1,309.8 seconds, whereas members averaged 743.5 seconds per ride.

## Top 5 Frequently Used Stations

### 1. Casual Riders

#### Start station names: 

1.  Streeter Dr & Grand Ave

2.  DuSable Lake Shore Dr & Monroe St

3.  Millennium Park

4.  Michigan Ave & Oak St

5.  DuSable Lake Shore Dr & North Blvd

#### End station names:  

1.  Streeter Dr & Grand Ave

2.  DuSable Lake Shore Dr & Monroe St

3.  Millennium Park

4.  Michigan Ave & Oak St

5.  DuSable Lake Shore Dr & North Blvd

### 2. Member Riders

#### Start station names

1.  Kingsbury St & Kinzie St

2.  Clark St & Elm St

3.  Wells St & Concord Ln

4.  University Ave & 57th St

5.  Clinton St & Washington Blvd

#### End station names 

1.  Kingsbury St & Kinzie St

2.  Clark St & Elm St

3.  Wells St & Concord Ln

4.  University Ave & 57th St

5.  Clinton St & Washington Blvd

## Recommendations and Conclusions

1.  **Docked Bike Membership Plans**: Introduce cost-effective membership options specifically for docked bike users who frequently travel long distances. These plans should highlight significant cost savings compared to single-ride purchases.

2.  **Seasonal and Peak-Time Discounts**: Offer discounts on electric and docked bikes during high-demand periods, such as weekends or months with the most rides, to attract casual riders toward memberships.

3.  **Targeted Station Campaigns**: Focus marketing efforts and promotional campaigns on the most popular start and end stations for casual riders, enhancing awareness of membership benefits at these locations.

This marks the end of my Google Data Analytics Capstone.
