# Genre Classification
This folder contains the exercise 14 from lesson 5 of Training Course 3 "Building a reproducible Model Workflow".

In order to run the inference make sure to add a commandline switch to use the conda environment:
```bash
mlflow models predict -t csv -i data/segregated_data_test.csv -m model --env-manager conda
```
