# US_Treasury_Data_Validation_Dashboard
Automated data scrubbing and yield curve visualization for US Department of the Treasury.
## What is this project?
I created this Excel workbook to help find and fix errors in US Treasury market data. It takes a list of government bonds and uses formulas to check if the prices and yields (interest rates) are correct.
## What does it do?
**Find Errors:** I wrote formulas to automatically flag when a bond price doesn't match its yield.
**Cleans Data:** It removes old or incorrect information so the final results are accurate.
**Creates a chart:** It plots a "Yield Curve" (a scatter smooth lines chart) that shows how yield change from 1 month to 30 years.
## Key Insights
The Final dashboard produces a "Normal" upward-sloping Yield Curve, essential for calculating corporate credit spreads and pricing derivatives like Credit Default Swaps (CDS).
## How to View
1. Download the '.xlsx' file from this repository.
2. The **Yield Curve** tab contains the "Executive view with the table and Yield Curve.
3. The **Raw Data** tab contains my audit notes and validation logic.
