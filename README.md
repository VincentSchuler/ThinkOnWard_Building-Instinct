# ThinkOnWard_Building-Instinct
4th place to competition "Building Instinct" hosted by ThinkOnWard.
Winner of the 1000$ Honorable Mention for Feature Engineering and Excellent Documentation.

# Solution Guidelines

Hi, here are some guidelines to run my solution.

Below is a brief description of the 3 notebooks provided.
To run inference, you just need to execute the third notebook (if you decide to use the `test.csv` file that I provided). This `test.csv` file can also be generated by notebook n°1, which takes approximately 2 hours and 30 minutes. Just take care of uploading competition files in the "Files/" folder before running the notebook.

## Notebooks Overview

### Notebook n°1: 1_Feature_extraction.ipynb
- **Purpose:** Generates `df_train.csv` and `df_test.csv` files.
- **Inference Requirement:** Only `test.csv` is mandatory to run inference.
- **Preparation:** Ensure you place the individual building test files in the `Files/building-instinct-test-data/` folder before executing the notebook. The same applies to the train files.

### Notebook n°2: 2_Training.ipynb
- **Purpose:** Trains and saves models.
- **Inference Requirement:** Does not need to be run for inference.

### Notebook n°3: 3_Inference.ipynb
- **Purpose:** Generates `submission.parquet` files.
