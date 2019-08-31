/************************************************************************************************************************/
/************Project Title: Recommended Categorical Price and Availability Prediction Using Deep Learning****************/
/*********************************************Name: Saad Hasan***********************************************************/
/****************************************Carleton ID: 101057121**********************************************************/
/********************************************SYSC-5900*******************************************************************/
/*******************************************Term: Summer 2019************************************************************/
/************************Department of Systems & Computer Engineering****************************************************/
/********Speicial Thanks to my supervisiors: Prof. Ioannis Lambadaris & Prof. Omair Shafiq for their valuable time*******/
/*************************************Carleton University, Ottawa, Canada************************************************/
/************************************************************************************************************************/

Programming Languages used: Python 3.7, R
Deep Learning Framework used: Keras (Tensorflow backend) 
Software for Execution: Google Colab or Jupyter Notebook

/**************************/
/****Files Organization****/
/**************************/
Data: Which contain all the data files in csv format
Images: Images drawn using python scirpting for visualization
Papers Studied: The number of papers review through the research work
Pseudo Code: Consist of Pseudo code to understand the basic flow of the methodology
Source Code: Contain all code files in ipynb format
Final Project Report: All the details and research discussed in the report using IEEE Conference paper format.


/*************/
/****Steps****/
/*************/
Instructions to run in Google Colab:
	torontouncleaned.csv ==> Representing the Original Dataset
	To install any library in google colab type
	!pip install (library name)
	For example: "!pip install numpy"

1. To run the model for the Price Prediction:
	1.1 Deep Learning Model
		1. Run SYSC_5900.ipynb in google colab
		2. Upload extractfeaturetoronto.csv

	1.2 Other algorithms comparision
 		1. Run SYSC_5900_Randorm_forest_Xgboost.ipynb 
		2. Upload cleanedtorontodata.csv

2. For Availability Prediction:
	2.1 Run the script AvailabilityPrediction.ipynb
	2.2 Upload data availabilitytoronto.csv

Instructions to run in Python Jupyter Notebook:
	All steps are same but requires installation of Python libraries by using the command in cmd
		"pip3 install (library Name)" 
		 For Example: "pip3 install numpy" 