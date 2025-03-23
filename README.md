# Replication Package for the paper entitled "FairPlay: Examining Fairness Issues in Machine Learning-based Systems"

Description of the content:

1) the [dataset](dataset) folder contains the **dataset.csv** file reporting issue reports and pull requests from the selected projects with titles containing fairness-related keywords.

2) the [study](study) folder contains the raw results used to answer the two research questions. In particular:
   - the subfolder [RQ1](study/RQ1) comprises the file **RQ1_results.xlsx** reporting the summaries generated for each issue report or pull request and the related evaluations.
   - the subfolder [RQ2](study/RQ2) contains the results of the labeling performed by the six raters to identify actual fairness-related concerns with associated observed behaviors, root causes, and likely solutions. More specifically: 
        - **RQ2_Subset 1** reports the raw results of the labeling performed by raters 1 and 2;
        - **RQ2_Subset 2** reports the raw results of the labeling performed by raters 3 and 4;
        - **RQ2_Subset 3** reports the raw results of the labeling performed by raters 5 and 6;
        - **RQ2_Clustering** reports the results of the clustering performed to group type categories.
