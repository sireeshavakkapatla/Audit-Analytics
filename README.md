This is an Impact Measurement Dashboard I created in Google Looker Studio using mock nonprofit data. The goal was to measure donation trends, program performance, and cost efficiency across regions and time, helping stakeholders assess overall impact.

## Highlight:

Purpose: Track KPIs such as Success Rate, Impact Ratio, and Cost Efficiency

Tools: Google Sheets + Looker Studio (live connection)

Automation Goal: Zero manual refresh for weekly trend reports

## Data Source & Modelling (Technical Depth)

“The dataset was stored in Google Sheets  covering Program, Cost, Donations, Beneficiaries, Donors, Date, Payment Method, Country, and City. I modeled the data directly in Sheets before connecting it to Looker Studio.”

Technical notes to mention:

Connected Google Sheets using live connection (auto-refresh enabled)

Cleaned and normalized data fields (Dates, Numbers, and Text formats)

Created derived fields:

### Success Rate = (Beneficiaries_Reached / Planned_Beneficiaries) * 100

### Cost per Beneficiary = Total_Cost / Beneficiaries_Reached

### Impact Ratio = Beneficiaries_Reached / Total_Donations

This shows you understand metric design and transformation logic.

## Automation & Data Refresh

“To make the dashboard dynamic, I used Google Sheets as a live data source. Any update in the sheet — such as new donations or program costs — automatically reflects in Looker Studio.

## Analytical Insights (Demonstrate Business Value)
Health program had the highest planned beneficiaries but slightly lower reach — improvement opportunity.
Cash and credit card payments contributed 70% of total donations — key fundraising channels.
USA showed best cost efficiency (lowest cost per beneficiary).
Overall success rate = 80.5%, showing strong program effectiveness.
