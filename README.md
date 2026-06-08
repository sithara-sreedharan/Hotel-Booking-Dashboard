# Hotel-Bookings-Dashboard
## 🏨 Hotel Bookings Dashboard – Property Performance & Guest Analysis
An interactive Power BI dashboard designed to monitor and analyze key hotel performance metrics, enabling property owners and executives to track reservation trends, revenue, and guest behavior. The dashboard transforms raw reservation data into actionable insights through dynamic visualizations, KPI indicators, and property-level reporting.
### 2. Purpose
The Hotel Bookings Dashboard is an executive reporting solution built in Power BI to provide a comprehensive view of a hotel's operational performance. The dashboard helps stakeholders monitor critical metrics such as Booking Count, Cancellation Percentage, Total Revenue, and Average Room Rate. Through intuitive visualizations, users can identify peak stay periods, analyze guest loyalty tiers, and understand booking lead times to optimize marketing and business decisions. This dashboard is suitable for hotel managers, property owners, and business analysts who require quick access to guest insights and revenue performance for strategic planning.
### 3. Tech Stack
The dashboard was built using the following tools and technologies:
📊 Power BI Desktop – Primary platform for dashboard development and interactive reporting
📂 Power Query – Used for data extraction, transformation, date subtraction, and creating categorical buckets for analysis. 
🧠 DAX (Data Analysis Expressions) – Used for calculating business measures including cancellation rates, total room nights, and average room rates. 
🔗 Data Modeling – Built on a structured booking dataset with calculated columns for revenue and stay durations.
 📈 Advanced Visualizations – New card visuals, shaded area line charts, and heat-mapped matrices.
📁 File Formats – .pbix for development and .png for custom canvas backgrounds.
4. Data Source
Source: Sample Dataset used in Chandoo's Power BI Dashboard Tutorial Series.
Description: The data includes detailed booking records featuring booking IDs, stay dates, room rates, booking channels (App, Website, Partners), and loyalty membership levels.
5. Features / Highlights
• Walkthrough of Key Visuals
KPI Summary Cards
Display five key indicators: Booking Count, Cancellation %, Total Revenue, Total Room Nights, and Average Room Rate using the modern Power BI card visual.

Stay Trend Analysis
An interactive line chart tracks "Stays per Day," supported by a date slicer to narrow analysis to specific timeframes and eliminate data noise.
Guest Loyalty & Channel Heatmap
A matrix visual utilizes conditional formatting to highlight "hot spots" where specific loyalty tiers (e.g., Iconic, Elite) intersect with booking channels.
Booking Lead Time
A categorical column chart displays how far in advance guests plan their stays, distinguishing between "impulse" weekly bookers and long-term planners.
#### Business Impact & Insights
•	Financial Visibility: Monitor critical financial KPIs, including Total Revenue and Average Room Rate, from a centralized dashboard to maintain a clear view of property health.
•	Performance Tracking: Measure business performance by tracking essential metrics such as Booking Count and Cancellation Percentage to evaluate operational success.
•	Trend Identification: Detect growth opportunities and potential risks early by analyzing stay patterns, such as higher mid-week occupancy for business travel versus weekend leisure stays.
•	Data-Driven Decisions: Enable executives to make informed strategic decisions by understanding guest behavior, such as identifying "impulse" bookers versus long-term planners and analyzing booking channel performance.
•	Operational Efficiency: Reduce manual reporting effort through automated KPI tracking that calculates complex data points like cancellation rates and stay-duration buckets instantly.
•	Executive Communication: Present property performance in a clear and visually compelling format
### 6. Key Power BI Concepts Demonstrated
• Power Query Data Transformation: Calculating revenue and lead-time buckets. 
• Date Logic: Adjusting week-start days and sorting day names chronologically rather than alphabetically. 
• DAX Context Manipulation: Using the CALCULATE function to isolate cancellation counts against total bookings. 
• Custom UI/UX: Custom padding, and plot area backgrounds for a "luxury" reporting feel. 
• Interactive Storytelling: Cross-filtering across visuals to see specific behaviors of "non-loyal" or "multi-night" guests.
### 7. Screenshots / Demos
Show what the dashboard looks like.

Example:![Dashboard Preview]( https://github.com/sithara-sreedharan/Hotel-Booking-Dashboard/blob/main/Snapshot%20of%20Hotel%20Booking%20Dashboard.png)

