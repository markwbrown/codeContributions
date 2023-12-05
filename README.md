# Git Commit Analysis Jupyter Notebook

## Overview
This Jupyter Notebook provides tools for analyzing Git commit data over time. It extracts commit details from a specified Git repository and branch, then processes this data to 
present insights into the contributions of different authors, including the amount of code added over various intervals.

## Features
- **Commit Data Retrieval**: Extracts commit data from a given Git repository and branch.
- **Data Analysis**: Analyzes commit data to determine the number of lines added by each author.
- **Time-Based Insights**: Provides insights in 30-day intervals.
- **Data Visualization**: Uses Pandas, Seaborn, and QGrid for data handling and visualization.

## Prerequisites
Ensure you have the following installed:
- Python 3.9.13 or higher
- Libraries: pandas, numpy, matplotlib, seaborn, GitPython, qgrid
- A local Git repository for analysis

## How to Use
1. **Setup**: Clone the repository containing this notebook to your local machine.
2. **Install Dependencies**: Install the required Python libraries (listed in `requirements.txt`).
3. **Launch Notebook**: Open this notebook in a Jupyter environment.
4. **Enter Repository Details**: Input the path to your local Git repository and the branch name when prompted.
5. **View Results**: Analyze and interact with the commit data presented in various formats, including tables and grids.

## Functionality Breakdown
- `get_commit_data`: Fetches commit data from the specified repository and branch.
- `analyze_commit_data`: Processes the commit data to create a summary of lines added per author in different time intervals.

## Visualization
- The notebook uses `matplotlib` and `seaborn` for plotting data.
- `qgrid` is used for interactive data grids, allowing sorting and filtering.

