# ProcureSense_Dataset_for_Realistic_Supply_Chain_Optimization
A hybrid procurement dataset combining real-world logic with synthetic anomalies to support ML-based forecasting, anomaly detection, and supply planning research. Includes features like demand, urgency, supplier reliability, and lead time

This repository provides a hybrid procurement dataset that combines authentic enterprise-like records with synthetic variations for robust training and evaluation of machine learning models in procurement planning, demand forecasting, and anomaly detection.

# Dataset Summary

Rows: 2,000
Columns: 11
File Format: CSV

The dataset simulates realistic supply chain behavior across various dimensions including supplier reliability, real-time demand variation, market dynamics, and procurement urgency.

# Sample Features
Column Name	Description
Product_ID	Unique identifier for each product
Historical_Demand	Past demand values aggregated over time
RealTime_Demand_Variation	Current demand deviation from average (normalized)
Supplier_Reliability	Confidence score (0–1) reflecting supplier consistency
Lead_Time_Days	Average delivery time in days
Procurement_Cost_Per_Unit	Unit procurement cost from supplier
Market_Price_Index	Market-relative price index (normalized)
Order_Frequency	Frequency of past orders (weekly count)
Stock_On_Hand	Available inventory at time of decision
Urgency_Flag	1 if item is urgently needed, else 0
Optimal_Procurement_Qty	Recommended procurement quantity for the scenario

# Use Cases
Multi-step demand forecasting
Supplier performance–aware procurement planning
Cost vs. urgency–driven decision optimization
Anomaly detection in cost spikes, lead times, or demand behavior
Training hybrid/ensemble AI models for supply chain intelligence

# File Structure
├── ProcureSense_Dataset.csv
├── README.md

# Related Research Paper

This dataset supports the findings in the paper:
“ProcureSense: A Multi-Branch Hybrid Model and Public Dataset for Realistic Supply Chain Optimization”

# If you use this dataset, kindly cite the paper:

@article{procuresense2025,
  title={ProcureSense: A Multi-Branch Hybrid Model and Public Dataset for Realistic Supply Chain Optimization},
  author={Your Name},
  journal={arXiv/IEEE/TBD},
  year={2025}
}
