# Exploratory data analysis: automotive examples

**Portfolio category: historical learning exercise.** This repository records foundations used in later health-data research. It is presented with its original scope and execution limits.

Two historical automotive exercises: a car-feature EDA walkthrough and a Carvana auction-data assignment. They cover data types, missingness, duplicate/outlier screens, grouping, categorical encoding and visualization.

Start with [Exploratory_data_Analysis.ipynb](Exploratory_data_Analysis.ipynb).
The second notebook is [Project EDA Nov 2022](Project%20EDA%20Nov%202022%20%281%29.ipynb).


## Reproduction

Create a dedicated Python environment and install the notebook's libraries:

```bash
python -m venv .venv
python -m pip install numpy pandas matplotlib seaborn scikit-learn jupyterlab
python -m jupyter lab
```

Restore the exact original source files and expected columns when local datasets are required. Read the notebook before executing it. These setup commands are starting instructions, not a tested dependency lock or a claim that the historical notebook is currently runnable.

## Review status and limits

data.csv and Carvana dataset.csv are not committed; the walkthrough retains a stored FileNotFoundError. These are exploratory teaching transformations, not validated production preprocessing. Missing-value deletion and IQR filtering require substantive justification, and encoded-category correlation is not evidence of causality. Original tutorial links and attribution remain in the notebook.

The October 2026 portfolio review inspected notebook code, syntax, stored errors and repository contents. It did not obtain missing datasets or independently re-execute every exercise. Original teaching provenance and source links remain authoritative for attribution and dataset rights.

For applied research, see the [dental AI survey](https://github.com/javed110/dental-ai-survey-pakistan) and [causal-method benchmark](https://github.com/javed110/parvovirus-b19-causal-ml-benchmark). Those projects document their methods, uncertainty and data-access boundaries separately.
