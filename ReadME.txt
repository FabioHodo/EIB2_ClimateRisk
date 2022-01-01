We have separated the work in two folders: the data cleaning (folder: cleaned data) and model fitting (folder: Model)

1) Cleaned data:
	- Data_raw contains the raw data files as downloaded from each websites i.e. CAIT, EIA, World bank.
	- data_imputed contains the imputation files and results
		1) Initially data was processed (cleaned by hand using Excel) to make ingestion easier
		2) After that we tried several imputation methods: imputed_KNN for K-nearest neighbors,
			imputed_PolyReg for Polynomial Regression, imputed_PolyReg&KNN for both
		3) Imputation.ipnyb contains all the code used and the Powerpoint "Imputation Methodolgy and Explantion" 
			contains the methodolgy used during our imputation and after. More details contained inside the jupyter ntbk.

2)Model Fitting.