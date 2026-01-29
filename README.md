🚛 Azerbaijan Freight Transportation EDA
A comprehensive Exploratory Data Analysis (EDA) of freight transportation trends in Azerbaijan, covering the period from 1995 to 2023 . This project visualizes the growth, structural shifts, and modal distribution of the logistics sector using historical data.

📊 Project Overview
The primary objective of this project is to analyze how goods are moved across Azerbaijan's transport corridors. By examining different transport modes (Road, Rail, Sea, Pipeline, and Air), we can identify economic patterns and infrastructure development milestones.

Key Analysis Steps:
Data Transformation : Converting wide-format historical data into a tidy "long" format for time-series analysis.

Trend Identification : Tracking the growth of total freight volume over 28 years.

Distribution Analysis : Comparing the market share of different transport modes in the latest available year.

Structural Shifts : Using Stacked Area Charts to visualize how the "logistics mix" has evolved.

Interactive Exploration : Multi-line Plotly charts for granular year-over-year comparisons.

Intensity Mapping : Normalizing data via heatmaps to find the historical "peak momentum" for each transport mode.

📂 Dataset Details
Source: IDDA Open Data Portal (Azerbaijan).

Unit of Measurement: Thousand tons.

Transport Modes Included: - Railway ( Dəmir yolu)

Sea (Dəniz )

Air (Hava )

Road (Avtomobil )

Pipeline (Boru kəməri )

🛠️ Installation & Setup
Prerequisites
Python: 3.13 or higher.

Data File: Ensure nqliyyat_sektorunda_yuk_danmas__min_ton_20250424140850.csvis in the project root.

Setup Instructions
Clone the repository:

Bash
git clone https://github.com/your-username/azerbaijan-freight-eda.git
cd azerbaijan-freight-eda
Install dependencies: You can install the required packages using pip:

Bash
pip install pandas matplotlib seaborn plotly numpy
🚀 Usage
Open the Jupyter Notebook to view the analysis and interactive visualizations:

Bash
jupyter notebook idda-eda.ipynb
📈 Key Visualizations & Findings
Total Volume Trend : A long-term upward trajectory indicating expanding trade and economic activity.

Dominant Modes : Road transport shows the most aggressive growth, while Pipeline transport provides the steady volume backbone.

The 2023 Snapshot : Clear visualization of which sectors currently handle the majority of freight throughput.

Peak Identification : The analysis pinpoints the specific historical year of maximum logistics output.

🏗️ Project Structure
Plaintext
.
├── idda-eda.ipynb           # Main analysis notebook with all steps & graphs
├── pyproject.toml           # Project metadata and dependencies
├── README.md                # Project documentation
└── [Data File].csv          # Raw freight transportation dataset
📝 License
This project is for educational and analytical purposes. Data is sourced from public portals; please credit the IDDA Open Data Portal when sharing results.
