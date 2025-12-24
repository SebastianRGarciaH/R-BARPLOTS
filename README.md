This script analyzes and visualizes antimicrobial resistance data from five databases 
(ARGannot, MEGARES, ResFinder, NCBI, and CARD). It performs data integration, 
calculates relative abundance of resistance types, and generates a stacked bar plot 
showing resistance composition by database.

Key features:
- Integrates resistance data from 5 different antimicrobial resistance databases
- Cleans and standardizes sample names across databases
- Calculates relative abundance of each resistance type per database
- Generates a publication-ready stacked bar plot with custom color palette
- Exports combined dataset to CSV for further analysis

Output files:
- barplot_resistance_by_DATABASE.png: Visualization of resistance composition
- resistance_all_databases.csv: Combined resistance data from all databases

Dependencies: tidyverse, readxl, RColorBrewer
COMMENTED WITH AI
