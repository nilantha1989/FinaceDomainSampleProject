<b>Overview</b>

  
  <p>This repository contains a Power BI dashboard for loan analysis, designed to provide insights into loan portfolios, repayment trends, risk assessment, and other key metrics.
The dashboard helps financial analysts and loan officers make data-driven decisions.</p>

<b>Features</b>
- Interactive visualizations showing loan distribution, repayment status
- Key performance indicators (KPIs) for portfolio health assessment
- Geographical mapping of loan distribution
- Custom filters for slicing data by loan type, region, etc.

<b>Repository Structure</b>


<details> <summary>Click to expand project structure</summary>
│── /data                 # Excel file 
│── README.md             # This file
Images
│   ├── 1049443.png
│   ├── 5690282.png
│   └── real-estate.png
├── LoanAnalysisDashboard.pbip
└── LoanAnalysisDashboard.pbix
</details>

Setup Instructions

  
Prerequisites
- Power BI Desktop
Installation

Clone this repository:
<p>
bash

git clone https://github.com/nilantha1989/FinaceDomainSampleProject.git

Open powerbi/LoanAnalysis.pbix in Power BI Desktop

If prompted, update data source connections to point to your local data files</p>

<b>Connecting to Your Data</b>

- In Power BI Desktop, go to "Home" > "Transform data" > "Data source settings"
- Update the paths or connection strings to point to your data sources
- Refresh the data using the "Refresh" button

<b>Key Metrics Calculated</b>
- MTD Avg Int Rate
- MTD Loan Applications
- Total Amount Received
- Total Funded Amount
- etc..
- 
<b>Customization</b>

To modify the dashboard:

  1. Open the PBIX file in Power BI Desktop
  2. Edit visuals in the "Report" view
  3. Modify measures and calculations in the "Data" view
  4. Adjust relationships in the "Model" view

<b>Troubleshooting</b>
- Data connection errors: Verify your data source paths and credentials
- Visual rendering issues: Check for filters that might be hiding data


<a href="https://example.com](https://app.powerbi.com/view?r=eyJrIjoiYTYyMGQ3MjctOWE2OS00MWEzLWJkYjktZmU5MzI0M2I3N2EyIiwidCI6IjE2NzAxMjgxLTZmNTQtNDE4OC1iNTY0LTIyMDNkYjBkMzM5YiJ9">View report online</a>

