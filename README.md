# HVAC-Supply-Chain-KPI-Dashboard

This project presents a one-page Power BI dashboard designed to monitor key supply chain and production KPIs for an HVAC factory.

Workflow:

	•	Performed data cleaning and handled missing values (replaced with Unknown).
 
	•	Built a star-schema model connecting inbound deliveries, production output, outbound shipments, and a loss hierarchy table.
 
	•	Structured the loss hierarchy into Level 1 → Level 2 → Level 3 categories for drill-down analysis.

KPIs implemented with DAX:

	•	OTIF Inbound – On Time In Full deliveries from suppliers.

	•	OTIF Outbound – On Time In Full shipments to customers.
 
	•	Inventory Days on Hand (DOH) – Stock cover based on demand.
 
	•	Scrap Rate % – Scrap relative to total production.
 
	•	Downtime Hours – Total recorded downtime.

Dashboard features:

	•	KPI cards for all key metrics at the top.
 
	•	Downtime trend chart to analyze daily losses.
 
	•	Line chart comparing inbound vs outbound OTIF performance.
 
	•	Drill-down tree visual for production losses (from high-level categories to detailed causes like equipment failure, material shortage, or power outage).
 
	•	Interactive slicers for date and KPI selection.

The dashboard provides an interactive, data-driven view of supply chain performance, enabling faster and more informed decision-making.
