Creating a simple ETL using Python and Divvy Bikes Data 

Overview

This project aims to analyze the Divvy bike-sharing system's data to derive insights into bike usage patterns, user behavior, and temporal trends. The analysis encompasses data from 2018, covering all four quarters of the year. The main objectives include:

Combining multiple CSV files containing trip data into a single dataset.
Aggregating and summarizing trip information by day of the week, quarter, month, and hour.
Visualizing key metrics to facilitate data-driven decision-making.
Project Structure
The repository is structured as follows:

Data: Contains the original CSV files with Divvy bike trip data for each quarter of 2018.
Scripts: Includes the Python scripts used for data processing, analysis, and visualization.
Results: Stores the output files generated during the analysis, such as pivot tables and visualizations.
README.md: This document, providing an overview of the project and instructions for usage.
Usage
Requirements
Python 3.x
Pandas
Seaborn
Jupyter Notebook (optional, for running scripts interactively)
Steps
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/KitAndre82/basic-ETL.git
Navigate to the project directory:

bash
Copy code
cd divvy-bikes-analysis
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Execute the main script to perform data processing and analysis:

bash
Copy code
python process_data.py
Explore the generated results in the Results directory.

Results
divvy_bikes_datawarehouse.xlsx: Excel file containing the pivot table summarizing bike trip data by various dimensions such as date, quarter, month, day of the week, hour, and user type.
Plots: Directory containing visualizations generated from the analysis, including histograms, scatter plots, bar plots, and line plots.
Contributing
Contributions to this project are welcome. Feel free to submit bug reports, feature requests, or pull requests to help improve the analysis and enhance its capabilities.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the Divvy bike-sharing system for providing access to their data, enabling this analysis.

