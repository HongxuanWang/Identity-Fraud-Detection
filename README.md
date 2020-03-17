# Identity-Fraud-Detection
The report provides a detailed description of how the team constructed and implemented an algorithm to identify identity fraud in the applications data provided. The data consists of 1,000,000 records and 10 fields, including existing fraud labels, which allowed the team to build a robust model capable of efficiently identifying fraudulent applications. 

Model building steps:

●	Description of Data: Overview of the most significant fields and their distributions.
●	Data Cleaning: Treatment of frivolous values and filling leading zeros. 
●	Candidate Variables: Creation of 253 candidate variables, from the original 8 fields.
●	Feature Selection: Z-Scaling, Univariate KS and FDR filters, and RFECV wrapper to identify the 27 best variables.
●	Model Algorithms: Implementation of the base linear model (Logistic Regression), and 3 non-linear models (Boosted Tree, Random Forest, and Neural Network) to calculate average FDR at 3%.
●	Results: Final model and parameter selection to create three statistics tables for training, testing, and OOT.
