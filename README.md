# Biodiversity in U.S. National Parks (Codecademy Data Analysis Project)

This repository contains a Codecademy Data Analysis project where we'll analyze National Park Service data on endangered species. The goal of the project is to investigate conservation statuses and to look for patterns or themes among species that become endangered.

Project objective

- Complete a project to add to my portfolio
- Use Jupyter Notebook to communicate findings
- Run an analysis on a set of data
- Become familiar with the data analysis workflow

Repository contents

- data/
  - raw/                # original downloaded datasets (CSV/JSON)
  - processed/          # cleaned data used in analysis
- notebooks/
  - biodiversity_analysis.ipynb  # main exploratory notebook with analysis and plots
- README.md             
- LICENSE               
- requirements.txt      # optional — pinned dependencies for reproducibility

Analysis

- Conservation status counts (e.g., Endangered, Threatened, Species of Concern)
- Distribution of endangered species across parks and taxonomic groups
- Patterns/themes in types of species that are more likely to be endangered (e.g., mammals, birds, plants, amphibians)
- Any correlations between park characteristics and numbers of endangered species (if park metadata is available)

Key questions explored in the analysis

- Which parks have the most endangered species?
- What taxonomic groups are most frequently listed as endangered or threatened?
- Are there observable patterns (geographic, taxonomic, or threat-type) among endangered species?
- How complete and clean is the NPS data and what cleaning steps are necessary to make it analysis-ready?

How to reproduce the analysis

1. Clone the repository:

   git clone https://github.com/bruno-pezzolo/Codecademy-Biodiversity.git

2. Install dependencies (if a requirements.txt is provided):

   pip install -r requirements.txt

   Or install common packages used in the notebook:

   pip install pandas numpy matplotlib seaborn jupyter

3. Start Jupyter Notebook and open the notebook:

   jupyter notebook notebooks/biodiversity_analysis.ipynb

4. Execute the notebook cells to reproduce the analysis, figures, and conclusions.

Findings and conclusions

- The Jupyter Notebook contains the full analysis and a discussion of findings. Summaries and key plots should be near the top of the notebook to make the results easy to find.

Contributing

- Contributions are welcome. If you want to suggest improvements, file an issue or open a pull request with your changes.
- If adding or updating datasets, please include provenance (source URL and download date) and a short note describing any cleaning steps.

Acknowledgements

- Codecademy for providing the Data Analysis project framework, learning materials and data

Author

- Bruno Pezzolo — https://github.com/bruno-pezzolo
