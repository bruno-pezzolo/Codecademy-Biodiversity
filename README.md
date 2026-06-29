# Biodiversity in U.S. National Parks (Codecademy Data Analysis Project)

This repository contains a Codecademy Data Analysis project where I analyze National Park Service data on endangered species across U.S. national parks. The goal of the project is to investigate conservation statuses and to look for patterns or themes among species that become endangered.

Project objective

For this project, you will interpret data from the National Park Service about endangered species in different parks.

You will perform some data analysis on the conservation statuses of these species and investigate if there are any patterns or themes to the types of species that become endangered. During this project, you will analyze, clean up, and plot data as well as pose questions and seek to answer them in a meaningful way.

After you perform your analysis, you will share your findings about the National Park Service.

Example Project

Example Biodiversity in National Parks Project

Project objectives

- Complete a project to add to your portfolio
- Use Jupyter Notebook to communicate findings
- Run an analysis on a set of data
- Become familiar with the data analysis workflow

Prerequisites

- Familiarity with Python and Jupyter Notebook
- Codecademy coursework: Data Visualization and Communicating Data Science Findings
- Python packages: pandas, numpy, matplotlib, seaborn (see optional requirements below)

Repository contents (suggested structure)

- data/
  - raw/                # original downloaded datasets (CSV/JSON)
  - processed/          # cleaned data used in analysis
- notebooks/
  - biodiversity_analysis.ipynb  # main exploratory notebook with analysis and plots
- README.md             # this file
- LICENSE               # optional — add a license if you want to share publicly
- requirements.txt      # optional — pinned dependencies for reproducibility

What I analyze

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

2. (Optional, recommended) Create and activate a virtual environment:

   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   .\\.venv\\Scripts\\activate  # Windows (PowerShell)

3. Install dependencies (if a requirements.txt is provided):

   pip install -r requirements.txt

   Or install common packages used in the notebook:

   pip install pandas numpy matplotlib seaborn jupyter

4. Start Jupyter Notebook and open the notebook:

   jupyter notebook notebooks/biodiversity_analysis.ipynb

5. Execute the notebook cells to reproduce the analysis, figures, and conclusions.

Notes on data

- Place the raw National Park Service dataset(s) into data/raw/. If the dataset is not included in the repo due to size or licensing, provide instructions or a link to the download source in the notebook and in a note file inside data/raw/.
- Keep processed/ data under data/processed/ and do not commit large intermediate files unless necessary. Consider adding data/raw/ and data/processed/ to .gitignore if the files are large.

Findings and conclusions

- The Jupyter Notebook contains the full analysis and a discussion of findings. Summaries and key plots should be near the top of the notebook to make the results easy to find.

Contributing

- Contributions are welcome. If you want to suggest improvements, file an issue or open a pull request with your changes.
- If adding or updating datasets, please include provenance (source URL and download date) and a short note describing any cleaning steps.

Acknowledgements

- National Park Service for the endangered species data
- Codecademy for providing the Data Analysis project framework and learning materials

Author

- Bruno Pezzolo — https://github.com/bruno-pezzolo

License

- This project does not include a license by default. If you want to share the repository publicly, consider adding a license such as MIT or CC-BY. Add a LICENSE file to the repository.

If you'd like, I can:
- Tailor the README to include the actual filenames in your repo (notebook name, data file names) — I can scan the repository to list them automatically.
- Add a requirements.txt and simple environment setup file (environment.yml) for reproducibility.
