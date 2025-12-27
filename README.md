# ML_Assignment_Part_2

Dataset generation : Using llm: juspay_dataset_generation.ipynb
<br>Final Implementation notebook : ML_assignment_part2.ipynb
<br>Summary of results : ML_Assignment_Part2_Results.html
<br>Dataset along with Data Card: Inside Dataset folder: dataset folder has datacard.json which is the datacard, which contains the prompt templates along with other details about the synthetic dataset generation.

## Important points:
1. Datacard (dataset/datacard.json) has correct templates for track a and track b dataset, however, the template for track c dataset is wrong (that is not being used). For track C, the generated dataset was wrong, so I derived track C dataset from track B dataset (responses were taken as queries and input code as code).
2. Likewise, the track C jsonl files ("track_c_train.jsonl" and "track_c_test.jsonl" are wrong, they are not being used, instead track c dataset is being derived from track b dataset in the "ML_assignment_part2.ipynb" notebook.
3. Before running "ML_assignment_part2.ipynb", please upload the dataset folder.
