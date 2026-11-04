Municipal Service Request Analytics – Bengaluru
1. Project Overview

This project focuses on analysing municipal citizen grievances in Bengaluru using Descriptive Analytics.

The study uses the BBMP Citizen Grievances dataset to understand the patterns of civic complaints, including complaint categories, monthly reporting trends, geographical distribution across wards, and grievance status.

2. Research Question

What are the patterns and trends in municipal citizen grievances in Bengaluru based on complaint category, geographical distribution, reporting frequency, and grievance status?

3. Research Objectives
To identify the most frequently reported types of municipal grievances.
To analyse the distribution of grievances across different wards.
To examine monthly trends in grievance reporting.
To study the distribution of grievances based on their recorded status.
4. Dataset

Dataset: BBMP Citizen Grievances

The dataset contains approximately 1.23 million records and 12 variables, including:

Complaint ID
Category and Sub Category
Grievance Date
Zone Name and Ward Name
Grievance Mode
Grievance Status
Staff Information
Rating

The dataset is used to examine municipal service request patterns in Bengaluru.

5. Tools and Technologies
R Programming
RStudio
R Markdown
ggplot2
dplyr
readr
lubridate
janitor
6. Type of Analytics

Descriptive Analytics

The project uses frequencies, percentages, summary tables, and graphical representations to understand historical municipal grievance records.

7. Visualizations

The project includes four major visualizations:

Complaint Category Distribution
Monthly Grievance Trends
Ward-wise Complaint Distribution
Grievance Status Distribution

All visualizations are created using the ggplot2 package in R.

8. Project Structure
text
CTY-08/
│
├── data/
│   └── Dataset file
│
├── outputs/
│   └── graphs/
│       ├── complaint_category.png
│       ├── monthly_trends.png
│       ├── ward_distribution.png
│       └── status_distribution.png
│
├── report/
│   └── CTY-08.html
│
├── R/
│
├── CTY-08.Rmd
├── CTY-08.Rproj
└── README.md

9. How to Run the Project
Download or obtain the BBMP Citizen Grievances dataset.
Place the dataset inside the data folder.
Open CTY-08.Rproj using RStudio.
Open CTY-08.Rmd.
Install the required R packages if they are not already installed.
Run or Knit the R Markdown file to generate the HTML report.
10. Project Location

Bengaluru, Karnataka, India

11. Conclusion

This project demonstrates how descriptive analytics and R programming can be used to understand municipal service request patterns.

The analysis provides an overview of frequently reported civic issues, geographical complaint distribution, monthly reporting trends, and grievance status in Bengaluru.