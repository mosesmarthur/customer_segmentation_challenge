# Customer Segmentation Challenge 

# Repository Structure

 customer_segmentation.ipynb - conda python 3.9 has all the codes of exploration - Background, analysis and findings are on the first cell.
 Folder 'graph' -  all the interactive graphs are generated during exploration are present in the folder

## Description of dataset
Use the data provided in the file customer_data_sample.csv and, through the use of visualizations and/or statistics answer the question:

"What are the most important factors for predicting whether a customer has converted or not?"

Converted customer is represented in the data in the field "converted", and the nature of what this conversion means is (intentionally) unknown in the context of the challenge.

# Fields

| field | explanation |
|---|---|
| customer_id | Numeric id for a customer
| converted | Whether a customer converted to the product (1) or not (0)
| customer_segment | Numeric id of a customer segment the customer belongs to
| gender | Customer gender
| age | Customer age
| related_customers | Numeric - number of people who are related to the customer
| family_size | Numeric - size of family members
| initial_fee_level | Initial services fee level the customer is enrolled to
| credit_account_id | Identifier (hash) for the customer credit account. If customer has none, they are shown as "9b2d5b4678781e53038e91ea5324530a03f27dc1d0e5f6c9bc9d493a23be9de0"
| branch | Which branch the customer mainly is associated with |
