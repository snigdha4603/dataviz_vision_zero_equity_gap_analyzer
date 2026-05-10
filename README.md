# Vision Zero Equity Gap Analyzer

This project explores equity and traffic safety in New York City using geographic and socioeconomic data. It includes an analysis notebook, interactive dashboards, data files, and visualization outputs.

## Contents

- `equity_safety_gap_analyzer.ipynb` - main analysis notebook with data processing, mapping, and chart generation.
- `lpi.csv` - dataset containing local performance indicators.
- `nyc_equity_safety.csv` - primary equity and safety data for NYC neighborhoods.
- `nyc_equity_safety.geojson` - geographic boundaries for mapping the data.
- `dashboard.html` - interactive dashboard output.
- `index.html` - landing page / main HTML view.
- `fig4_scatter.html` - standalone scatter plot visualization.
- `bivariate_legend.json` - configuration or legend data used for bivariate mapping.
- `equity_safety_gap_slide_deck.pdf` - presentation deck for the project.
- `fig1_three_layers.png`, `fig2_bivariate_choropleth.png`, `fig3_gap_map.png`, `fig5_svi_themes.png`, `fig6_borough_summary.png`, `newplot.png` - exported visualizations.

## Description

This analysis focuses on identifying equity gaps in NYC's Vision Zero traffic safety efforts. It combines spatial data with demographic and safety indicators to visualize areas that may need more equitable investment and intervention.

## Getting Started

1. Open `equity_safety_gap_analyzer.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the notebook cells to load the data, perform analysis, and generate visualizations.
3. View the generated dashboards in `dashboard.html` and `index.html`.
4. Inspect `fig4_scatter.html` for a standalone scatter visualization.

## Notes

- The notebook likely depends on common Python libraries such as `pandas`, `geopandas`, `folium`, and `plotly`.
- Data files are stored in CSV and GeoJSON formats.

## License

No license is specified. Copying or reuse should be done with permission from the project owner.
