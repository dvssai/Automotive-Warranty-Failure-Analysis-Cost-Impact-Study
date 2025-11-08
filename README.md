Project Title: Automotive Warranty Failure Analysis & Cost Impact Study
Overview

This project analyzes 100 real automotive warranty service records to identify failure patterns, cost drivers, and part-level reliability issues. The focus is on steering wheel–related warranty claims, where a significant number of repairs result in full component replacement — suggesting systematic manufacturing or supplier quality gaps, not random customer usage.

Objectives

Analyze warranty claim data to detect failure mode patterns

Identify parts and labor operations driving cost escalation

Quantify repair cost impact at platform and plant levels

Convert unstructured customer complaint text into meaningful failure categories

Provide data-backed recommendations for quality and cost reduction

Key Insights
Insight	Business Impact
78% of cases required complete steering wheel replacement	Indicates design/manufacturing quality leakage
Full-Size Trucks = 52% of all affected vehicles	High-margin segments are absorbing avoidable warranty cost
Avg repair cost = $531 per case	$53k+ burn rate in just the sample window
25% failures occur within first 6 months	Early-life failures damage brand trust & drive repeat dealer visits
Complaint themes include Material Damage, Heating Faults, Driver Assist Issues, Horn Switch Faults, and Steering Noise	Clear direction for root cause isolation and design review
Tech Stack
Area	Tools Used
Data Processing	Python (Pandas, NumPy)
Visualization	Matplotlib, Seaborn, Plotly
Text Categorization	Custom NLP keyword tagging
Output	Jupyter Notebook & HTML/PDF Reports
Data Workflow

Data Cleaning

Missing value treatment

Column normalization

Outlier detection via IQR approach

Exploratory Data Analysis

Platform-level distribution

Part failure frequency mapping

Date-wise cost aggregation

Region and plant-level comparisons

Failure Mode Tagging (NLP)

Categorized customer complaint text into structured failure modes

Cost & Business Impact Interpretation

Identified high-impact parts and regions

Recommendations

Immediate: Audit steering wheel suppliers for Full-Size Truck platforms.

Short-term: Strengthen material & stitching quality checks.

Mid-term: Conduct design/thermal control review for heated steering modules.
