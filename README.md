# NER_tag_extraction
This notebook processes clinical trial data to generate named entities (NERs) tags using a SpaCy-based model, taking conditions, official titles,  and inclusion criteria into account. The generated entities are appended as new columns and exported  to an Excel file for further analysis.
## Features
- Utilizes a pre-trained SpaCy model for NER.
- Processes three key fields: Official Titles, Conditions, and Inclusion Criteria.
- Exports processed data with additional NER columns to an Excel file.

## Requirements
- Python 3.11
- Libraries: SpaCy, pandas, openpyxl

## How to Use
1. Ensure the required libraries are installed using `pip install spacy pandas openpyxl`.
2. Update the `test_text` variable with relevant text for testing the model.
3. Run all the cells sequentially to process the dataset and export results.

## Output
The output Excel file `NERs_Offtitle_cond_incl_crit.xlsx` contains the original data along with three new columns for NERs:
- `NER_Officialtitle`
- `NER_Condition`
- `NER_inclusion_criteria`
