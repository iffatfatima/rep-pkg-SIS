### Replication Package for the paper titled "Quantifying Sustainability Impact during Software Architecture Evaluation via a Sustainability Impact Score (SIS)"


The repository is structured as follows:

- In /data, [data.xlsx](data/data.xlsx) contains the data on the quality attribute (QA) definitions, prioritization data, SQ Model, DMatrices, and summary of final SIS results.
  
- In /templates, [sis-template.xlsx](templates/sis-template.xlsx) contains a template for the DMatrix to calculate using the embedded formula. To use this template, replace the QA# with your quality attributes and the P# with a priority value. The SIS value will automatically calculated in the first cell of the sheet once you fill in the impact values per QA. The sheet only accepts numerical values. There is no limit on the number of QAs used. 

The IT architecture under evaluation can be found at [multi-model.nl](https://multi-model.nl)
