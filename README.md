# Privacy-in-dialogue-systems-analysis
An analysis of dialogue system logs with regard to private/sensitive information

## Contents
This analysis focuses on the detection of private user data in commercial dialogue systems' stored user inputs.

## Data
The files *data_analysis Google.ipynb* and *data_analysis Amazon.ipynb* include all the analyses performed on the logs of commercial dialogue systems.
The datasets themselves are not made publicly available since they contain private user information.
However, bits of the data can be found in the Jupyter Notebook for better understanding.

## Analysis
The analysis contains....
* ... sentence embeddings for all user inputs
* ... dimension reduction via Principal Component Analysis for visual representation of user input
* ... k-means clustering of inputs to detect patterns

## Python packages needed for analysis
* sentence_transformers
* pandas
* sklearn
* matplotlib