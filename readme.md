# Employee Performancen Analysis

## Overview

This repository contains scripts and tools for analyzing employee performance data. The purpose of this analysis is to gain insights into individual employee performance metrics and make data-driven decisions to enhance productivity and efficiency within the organization.

## Contents

1. **data**: This directory contains three sub folders containing
    - external
    - Processed
    - raw
        - The **external** and **raw** folder contains the original datasets.
        - The **Processed** folder contains the processed csv file containing the updated data after pre-processing.

2. **reference**: This directory contains the reference document for the variables and models which used and files generated.

3. **src**: This directory contains the implementation of the analysis and seperated into 3 subfolders.
    - data processing
    - models
    - visualisation
        - The **data processing** folder contains the **Exploratory Data Analysis** and the **PreProcessing** part of analysis. Also a dataset containing with the encoded values for the required columns or features and named as **encoded_data.csv**.
        - The **models** folder contains the implementation of the various models and also contains the the corresponding **.pkl** file containing the implemented model for the analysis.
        - The **visualization** This directory contains the plots for the models implemented and makes easier to make the decisions.

## Expected Results

And the following bellow are expected.
    1. Department wise performances.
    2. Top 3 Important Factors effecting employee performance.
    3. A trained model which can predict the employee performance based on factors as inputs.
    4. Recommendations to improve the employee performance based on insights from the analysis.

## Contributing

Contributions to this repository are welcome! If you have suggestions for improvements or new features, please submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## Contact

For any questions or inquiries about this project, please contact please visit vishnupriyan.in
