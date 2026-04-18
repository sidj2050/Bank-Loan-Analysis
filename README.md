In the banking industry, data is only as valuable as its reliability. I recently developed a Bank Loan Analysis Dashboard that transforms raw backend data into a high-impact command center for lending performance and risk management.

🛠 The Technical Architecture: SQL & Power Query
The journey began by connecting SQL Server to Power BI to ingest the raw lending datasets. To ensure the highest data integrity, I performed the entire ETL process within Power Query. This involved:

Data Profiling: Rigorous quality checks to identify outliers and missing values.

Transformation: Structuring complex banking data to ensure accurate calculations for a $435.8M portfolio.

Optimization: Streamlining the data model to support real-time interactivity.

📊 Deep-Dive Project Analysis
The dashboard is built on a three-tier architecture—Summary, Overview, and Details—to provide a comprehensive narrative:

Executive KPI Suite: I engineered the "Summary" view to track five core metrics: Total Applications (38.6K), Funded Amount, Received Amount, Interest Rates (12%), and DTI (13.3%). Using Advanced DAX, I implemented MTD and MoM indicators to track lending velocity.

Credit Quality Segmentation: I developed logic to visualize that 86.2% of the portfolio is healthy, while the 13.8% "Charged Off" rate identifies a $65.5M risk area.

Geospatial & Behavioral Trends: The "Overview" tab utilizes heat maps and trend lines to identify regional concentrations and seasonal shifts, such as the peak of 4.3K applications in December.

Advanced Interactivity: I integrated multi-dimensional slicers for Loan Grade, State, and Purpose. Whether it’s analyzing "Grade D" debt consolidation or "Grade A" home improvements, the visuals respond dynamically to every click.

This project highlights the power of Power Query ETL and Advanced Power BI visualization—turning "noise" into a clear strategic advantage for financial decision-makers.
