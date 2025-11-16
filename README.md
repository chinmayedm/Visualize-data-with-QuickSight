
# Visualize data with QuickSight
![Dashboard](https://github.com/chinmayedm/Visualize-data-with-QuickSight/blob/main/Screenshot%202025-11-16%20at%2019.01.41.png?raw=true)

# What is Amazon QuickSight?

Amazon QuickSight is a cloud-based business intelligence (BI) tool that enables interactive data visualization, reporting, and analytics. It is useful for creating dashboards, generating insights from data, and scaling easily across organizations.

# How I used Amazon QuickSight in this project

I used Amazon QuickSight to visualize Netflix data and trends by importing datasets, creating interactive dashboards, and generating insights on user preferences, viewing patterns, and popular genres. It visualizes simplified analysis effectively.

# One thing I didn't expect in this project was...

One unexpected aspect was how seamlessly Amazon QuickSight integrates with diverse data sources, enabling real-time analysis. It significantly reduced the time needed for data preparation and visualization compared to tools I’ve used before.

# Upload project files into S3

S3 is used in this project to store manifest.json, updated with the S3 bucket URL for data integration, and netflix_titles.csv, a dataset of Netflix metadata for analysis and visualization.

I edited the manifest.json file by adding the S3 bucket URL to specify the location of the Netflix dataset stored in Amazon S3. It’s important to edit this file because it ensures that the data source is correctly linked, enabling seamless access.

![S3 bucket](https://github.com/chinmayedm/Visualize-data-with-QuickSight/blob/main/Screenshot%202025-11-16%20at%2019.02.50.png?raw=true)

# Create QuickSight account

Creating a QuickSight account costs $0, but make sure to uncheck the “Paginated Reports” checkbox. 
Creating an account took me around 2 minutes.
![QuickSight account](

# Download the dataset

I connected the S3 bucket to QuickSight by visiting the S3 bucket and copying the URL from the manifest.json file. The manifest.json file was important in determining how your dataset looks, so QuickSight knows how to show it in charts or graphs.

# My first visualization

To create visualizations in QuickSight, I added release_year to the Y-axis, displaying a breakdown of the release years for Netflix TV shows and movies.

The chart/graph here is a breakdown of Netflix content by release_year. The chart highlights the total count of records grouped by release year, while the bar graph further categorizes the content into Movies, TV Shows, and Other types.

I created this graph by dragging and dropping the release_year field into the Y-Axis heading and the type field into the Group/Color heading.

# Using filters

Filters are useful for narrowing down data to focus on specific subsets, enabling more precise analysis. They help eliminate irrelevant information, highlight trends, and customize visualizations to answer targeted questions or meet specific objectives.

This visualization is a breakdown of Netflix content by release year and type (Movies, TV Shows, and Others). Here I added a filter by release year and content type to highlight trends, such as the distribution of titles over time and the popularity of content.

# Setting up a dashboard

As a finishing touch, I edited the titles in my charts so that anyone can understand them at a glance.

Did you know you can export your dashboard as PDFs too? I did this by selecting the Export icon and choosing Generate PDF, waiting for the PDF to be ready, then selecting Download. Now you can have a copy of the dashboard.
