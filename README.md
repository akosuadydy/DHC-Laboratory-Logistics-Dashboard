DHC Laboratory Inventory Optimization & Diagnostic Capacity Analysis

Project Overview
Completed as a hands-on data simulation on DataSims, this project evaluates diagnostic supply chain disruptions and inventory bottlenecks at DHC Laboratory. 

The primary objective was to quantify the operational impact of stockout events on diagnostic testing capacity and establish an automated inventory control system (Reorder Points & Safety Stock) to prevent future diagnostic disruptions.

---

Business Problem & Key Findings

Stockouts in clinical diagnostic kits directly compromise patient care and diagnostic throughput. Key findings from the analysis include:

Stockout Duration: Malaria RDTs suffered 34 stockout days, while Typhoid RDTs experienced 37 stockout days.
Lost Diagnostic Capacity: Stockout events resulted in an estimated*696 missed diagnostic tests across key panels:
157 missed Malaria tests
159 missed Typhoid tests
380missed H. Pylori tests

Demand Surges: Identified peak daily consumption spikes up to 14 tests/day for Malaria RDTs, highlighting the need for dynamic safety buffers.

---

Tools & Technologies
* Power BI Desktop: Data modeling, interactive visual creation, and DAX calculations.
* DAX (Data Analysis Expressions): Calculated measures for missed tests, stockout durations, and dynamic reorder logic.
* Microsoft Excel: Data cleaning, initial data inspection, and structural validation.

---

Dashboard Architecture & Visual Features
Executive KPI Cards: High-level executive overview of stockout days and calculated Reorder Points (ROP).

Interactive Slicers: Dynamic filtering by Product Category, Evaluation Year, and Specific Test Type.

Operational Capacity Impact Chart: Clustered column chart contrasting completed vs. missed tests across diagnostic products.

Daily Demand Trend Lines: Time-series analysis tracing daily consumption spikes relative to minimum inventory safety thresholds.

Key Recommendations
Implement Automated Reorder Point (ROP): Establish a minimum reorder trigger of 196 units for high-demand diagnostic kits to accommodate 14-day supplier lead times.

Maintain Safety Buffer: Establish a baseline safety stock buffer of 103 to 132 units to absorb unexpected demand surges (up to 14 units/day).

Real-time Stock Alert Tracking: Integrate real-time balance alerts into the Power BI view for immediate procurement action when stock reaches critical levels.
