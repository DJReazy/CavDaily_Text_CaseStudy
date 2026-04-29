# Cav Daily Text Analysis Case Study

## Overview
This case study explores how language differs between News and Opinion article titles from *The Cavalier Daily*. Students will use basic text analysis techniques to compare word usage patterns and determine whether these differences are statistically significant.

## Objective
The goal of this case study is to introduce students to:
- Bag-of-words text analysis
- Word frequency comparison
- Basic statistical testing (chi-square test)
- Interpreting results from real-world text data

## What You Will Do
You will analyze two datasets of article titles (News and Opinion) and:
1. Identify the most frequently used words in each group
2. Compare differences in word usage
3. Perform a chi-square test to evaluate whether these differences are significant
4. Interpret your findings in a short written report

## Repository Structure


UVA_DS_4002_Group_4_Project_1_text_data/
│
├── DATA/
│   ├── News_Uncleaned.csv
│   ├── News_Cleaned.csv
│   ├── Opinion_Uncleaned.csv
│   └── Opinion_Cleaned.csv
│
├── OUTPUT/
│     ├── News/
│         ├── news_cleaned_summary.csv
|         ├── news_token_length_distribution.png
|         ├── news_top10.png
|         ├── news_top20_words.png
|         └── news_word_frequency_distribution.png
│     ├── Opinion/
│         ├── opinion_cleaned_summary.csv
|         ├── opinion_token_length_distribution.png
|         ├── opinion_top10.png
|         ├── opinion_top20_words.png
|         └── news_word_frequency_distribution.png
|   ├── title_length_boxplot.png
│   └── word_frequency_table.csv
│
├── SCRIPTS/
│   ├── Analysis.ipynb
│   ├── Cleaning.ipynb
│   └── mi2ds4002.py
│
├── REFERENCES/
|   ├── bag_of_words_explainer.pdf
|   ├── chi_square_reference.pdf
|
├── Case Study Rubric.pdf
├── Do Headlines Tell Different Stories_.pdf
└── README.md


## Getting Started

1. Download the repository
2. Open `Analysis.ipynb` in Jupyter Notebook or VS Code
3. Run the notebook step-by-step
4. Use the outputs to guide your analysis
5. Refer to the rubric for full instructions

## Notes
- The dataset has already been cleaned to allow you to focus on analysis
- Example outputs are provided for reference only
- Your results may vary slightly depending on implementation

## Deliverable
A short written report (1–2 pages) summarizing your findings, including:
- Word frequency comparisons
- Visualizations
- Chi-square test results
- Interpretation of results


