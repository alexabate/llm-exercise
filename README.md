# llm-exercise

## Installation instructions

Requirements:
* Python 3.11 (recommended)
* LM Studio

1. Set up python environment: install packages specified in `requirements.txt`
2. Download and install LM Studio
3. Open LM Studio application, find and download `meta-llama-3.1-8b-instruct` using the search facility
4. In the Developer section load the `meta-llama-3.1-8b-instruct` model
5. Check the host url and port that is serving the model, it is probably `http://localhost:1234/`

## Contents

* applied-llm.html: Saved output from one instance running the notebook
* applied-llm.ipynb: Code and documentation is provided in a runnable jupyter notebook
* labelled.csv: hand labelled dataset
* output_df.csv: final output
* requirements.txt: python package requirements
* shopping_queries_dataset_examples.parquet: dataset downloaded from amazon-science/esci-data repo
* shopping_queries_dataset_products.parquet: dataset downloaded from amazon-science/esci-data repo
* shopping_queries_dataset_sources.csv: dataset downloaded from amazon-science/esci-data repo
* validation_sample_labelled.csv: a labelled validation sample

