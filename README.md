# Panalyze Interactive Dashboard

An interactive web application for exploring Pangenome Variation Graph (PVG) results from the [Panalyze](https://github.com/downingtim/Panalyze) pipeline.

This dashboard reads directly from a Panalyze `results/` directory to provide dynamic, zoomable visualizations for key outputs, including Pangenome Growth (Heaps' Law), Panacus node growth, and VCF mutation density. It replaces static PDFs with interactive charts to make data exploration more intuitive.

## 🚀 Features

*   **Pangenome Growth**: Interactive line chart for Heaps' Law analysis.
*   **Graph Complexity**: Grouped bar charts for Panacus node growth based on coverage and quorum.
*   **Mutations & PAVs**: Interactive histogram of mutation density across the genome, with embedded PDFs for PAVs.
*   **Openness Metrics**: View Pangrowth and Core Genome Growth plots directly in the browser.
*   **Phylogeny & Visuals**: Display the RAxML tree and provide download links for extremely wide VG/ODGI images.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rajithadp/panalyze-dashboard.git
   cd panalyze-dashboard

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt

## ▶️ Usage

1. Ensure you have a completed Panalyze results/ directory.
2. Launch the Streamlit app:
    ```bash
    streamlit run app.py
3. In the dashboard's sidebar, enter the path to your results folder (e.g., ../results) and explore the interactive charts.

## 👤 Author
Rajitha - [GitHub Profile](https://github.com/rajithadp)

## 📄 License
This project is licensed under the MIT License.


