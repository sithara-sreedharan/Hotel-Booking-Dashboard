# Hotel-Bookings-Dashboard
## 🏨 Luxury Hotel Reservation Dashboard – Property Performance & Guest Analysis

### About the Project
The goal of this project is to provide the chief executive or property owner of "Velora Luxury Hotel" with a comprehensive view of business performance. The dashboard analyzes 5,000 reservations spanning September and October 2024 to help stakeholders understand customer behavior, booking trends, and revenue metrics.

### Built With
•	Power BI: Used for the entire end-to-end analytical process, including data connection, transformation, and visualization.

•	Power Query: Utilized for data cleaning and feature engineering.

•	DAX (Data Analysis Expressions): Used to create custom business logic and key performance indicators.

•	PowerPoint: Employed to design a professional canvas background and the company logo.

•	ChatGPT (AI): Assisted in generating the brand logo and a cohesive eight-color palette for the custom theme.

### Data Source and Data Preparation
The data was sourced from a sample Dataset used in Chandoo's Power BI Dashboard Tutorial Series.

Key transformations included:

•	Revenue Calculation: Multiplying the number of nights by the room rate.

•	Lead Time Analysis: Subtracting the booking date from the stay date to determine how far in advance customers plan.

•	Data Bucketing: Categorizing lead times into groups such as "Before 1 week," "2 weeks," etc., to simplify trend analysis.

•	Date Formatting: Extracting day names and assigning day-of-week numbers to ensure correct chronological sorting (e.g., Monday to Sunday) rather than alphabetical.

### Data Modeling

While this specific demonstration utilized a single flattened table for simplicity, the project reflects a semantic modeling approach where facts (bookings) and dimensions (dates, loyalty levels) are structured to support complex filtering and interactivity.

### DAX Measures

The dashboard features several key business metrics calculated using DAX:

•	Booking Count: COUNTROWS of the bookings table.

•	Cancellation %: A DIVIDE function comparing the count of cancelled bookings (filtered via CALCULATE) against the total booking count.

•	Total Revenue: A SUM of the calculated revenue column.

•	Total Room Nights: A SUM of the total nights stayed across all bookings.

•	Average Room Rate: The total revenue divided by the total room nights.

•	Multi-night Booking Count: CALCULATE used to identify stays longer than one night.

### Dashboard Features
•	Interactive KPI Cards: Uses the "New Card" visual to display top-level metrics like Revenue and Cancellation Rate with a modern UI.

•	Relative Date Slicer: Allows users to narrow analysis to specific stay periods.

•	Trend Analysis: A line chart showing the daily stay volume with shaded areas for better visualization.

•	Stay Behavior Visuals: Column charts identifying peak stay days (Weekdays vs. Weekends) and lead-time buckets.

•	Loyalty Heat Map: A matrix visual using conditional formatting (color scales) to highlight hot spots for bookings across different loyalty tiers and booking channels.

•	Cross-Filtering: Selecting any element (like a specific loyalty level or date) automatically updates all other visuals to show related data.

### Insights
•	Customer Profile: A significant portion of the hotel's business comes from non-members, though lower-tier loyalty programs show healthy participation.

•	Booking Habits: The hotel caters heavily to "impulse" customers, with the majority of bookings occurring within one week of the stay.

•	Business vs. Leisure: Peak stays occur on Tuesdays and Thursdays, suggesting a strong business hotel profile rather than purely leisure.

•	Stay Duration: Over 50% of bookings are for multiple nights, indicating the hotel is a preferred choice for more than just overnight stops

### Screenshots / Demos
Show what the dashboard looks like.

Example:![Dashboard Preview]( https://github.com/sithara-sreedharan/Hotel-Booking-Dashboard/blob/main/Snapshot%20of%20Hotel%20Booking%20Dashboard.png)

