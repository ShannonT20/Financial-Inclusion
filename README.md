# Financial Inclusion Prediction Challenge

Welcome to the Financial Inclusion Prediction Challenge! This README provides instructions on setting up the project, running the code, and submitting your predictions.

## About project
Financial inclusion remains one of the main obstacles to economic and human development in Africa. For example, across Kenya, Rwanda, Tanzania, and Uganda only 9.1 million adults (or 14% of adults) have access to or use a commercial bank account.

Traditionally, access to bank accounts has been regarded as an indicator of financial inclusion. Despite the proliferation of mobile money in Africa, and the growth of innovative fintech solutions, banks still play a pivotal role in facilitating access to financial services. Access to bank accounts enable households to save and make payments while also helping businesses build up their credit-worthiness and improve their access to loans, insurance, and related services. Therefore, access to bank accounts is an essential contributor to long-term economic growth.

The objective of this competition is to create a machine learning model to predict which individuals are most likely to have or use a bank account. The models and solutions developed can provide an indication of the state of financial inclusion in Kenya, Rwanda, Tanzania and Uganda, while providing insights into some of the key factors driving individuals’ financial security.

### Evaluation

The evaluation metric for this challenge is Mean Absolute Error (MAE), where:
- `1` indicates that the individual does have a bank account
- `0` indicates that they do not have a bank account.

##### Submission File Format

Your submission file should have the following format:

| unique_id                | bank_account |
|--------------------------|--------------|
| uniqueid_1 x Kenya       |      1       |
| uniqueid_2 x Kenya       |      0       |
| uniqueid_3 x Kenya       |      1       |

Replace `<string>` with the actual unique identifier and `<number>` with the corresponding value indicating the presence (1) or absence (0) of a bank account.

## Data

The dataset for this challenge is available as train,test,variabledefinition and sample submission. Ensure you have the necessary CSV files before running the code.

## Submission

Ensure your submission file adheres to the specified format in the competition guidelines.

1. **Submit predictions to Zindi:**
    ```bash
    submission.csv
    ```
## Additional Resources

for more information contact me on shannosikadi@gmail.com
