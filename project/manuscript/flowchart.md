  ```mermaid
  flowchart  TD;
  S1[Raw data]-->S2[Cleaned Data \n Removed irrelevant columns for prediction] 
  S2-->S3[Preprocessed Data \n Rescaling by MinMax]
  S3-->S4[Split the dataset into training and testing sets with an 80:20 ratio]
  S4-->S5[Linear Regression]
  S4-->S6
  S5-->S7
  S6-->S7[Performance Comparison using MAE]

subgraph S6[ANN]
  style S6 fill:#aaa3dc,stroke:#333,stroke-width:2px;
  1[Model 1]
  2[Model 2]
  3[......]
  style 3 fill:#aaa3dc,stroke:#333,stroke-width:0px;
  4[Model 81]
end
  ```