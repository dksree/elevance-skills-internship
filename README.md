This project demonstrates multiple interactive data visualizations using Python and Plotly based on the Google Play Store dataset. Each task applies different filters, transformations, and visualization techniques to analyze app data effectively.

Technologies Used:-
Python
Pandas
Plotly
Google Colab
GitHub
Dataset

Dataset used:-Google Play Store Dataset
Key columns used:
App
Category
Rating
Reviews
Size
Last Updated
Android Version
Content Rating
Price

Tasks Implemented

Task 1:-
Grouped Bar Chart – Rating vs Reviews
A grouped bar chart compares the average rating and total reviews for the top 10 app categories.
Filters applied:
App size greater than 10 MB
Last update in January
Average rating ≥ 4.0
Visible only between 3 PM – 5 PM IST

Task 2:-
Choropleth Map – Global Installs by Category
An interactive Choropleth map visualizes installs across countries for the top 5 app categories.
Filters applied:
Categories not starting with A, C, G, S
Highlight categories with installs > 1 million
Visible only between 6 PM – 8 PM IST

Task 3:-
Dual Axis Chart – Installs vs Revenue
A dual-axis chart compares average installs and revenue for free vs paid apps within the top categories.
Filters applied:
Installs > 10,000
Revenue > $10,000
Android version > 4.0
Size > 15 MB
Content rating = Everyone
App name length ≤ 30 characters
Visible only between 1 PM – 2 PM IST

Task 4:-
Time Series Line Chart – Install Trends
A time series chart shows install trends over time by category.
Filters applied:
Reviews > 500
Categories starting with E, C, B
App names not starting with X, Y, Z
App name should not contain S
Categories translated into different languages:
Beauty → Hindi
Business → Tamil
Dating → German
Visible only between 6 PM – 9 PM IST

Task 5:-
Bubble Chart – App Size vs Rating
A bubble chart analyzes the relationship between app size and rating, with bubble size representing installs.
Filters applied:
Rating > 3.5
Reviews > 500
Installs > 50,000
Specific categories included:
Game
Beauty
Business
Comics
Communication
Dating
Entertainment
Social
Events

Additional features:
Game category highlighted in pink
Category translations applied
Visible only between 5 PM – 7 PM IST

Task 6:-
Stacked Area Chart – Cumulative Installs
A stacked area chart visualizes cumulative installs over time for each category.
Filters applied:
Rating ≥ 4.2
Reviews > 1,000
App name should not contain numbers
Categories starting with T or P
App size between 20 MB – 80 MB
Legend translations:
Travel & Local → French
Productivity → Spanish
Photography → Japanese
Visible only between 4 PM – 6 PM IST

Time-Based Visualization Logic
Each visualization is configured with a time restriction using Python’s datetime module. The graph appears only within the specified time window and remains hidden outside that range.

CONCLUSION
This project demonstrates how data preprocessing, filtering, and advanced visualization techniques can be used to analyze mobile app data effectively. By using interactive Plotly charts, the project highlights patterns in app installs, ratings, revenue, and category trends.
