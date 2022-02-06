Introduction: 
This analyses aims to categorise chest xrays into a total of 15 classes, of which 14 comprise pathologies. 

Data: 
The dataset used is the NIH Chest X-ray Dataset. 
The dataset contains a total of 112,120 frontal-view X-ray images of a total of 30,805 unique patients. 
The images are labeled to provide information on a total of 14 pathologies & a 'No Finding' class, totaling 15 classes. 
The dataset is heavily imbalanced with the minarity class 'Hernia' occuring only 227 times (0.2% of data). 

Methodology: 
CNN models are constructed for classification, which are founded on the 'ResNet50' and 'VGG19' structures for feature reduction. 
Weights are imported and a final set of layers are trained for classification on the problem set. 

Files: 
	Data Files: 
	The data files are available in the following GDrive Locations.
	Train file: https://drive.google.com/file/d/1-wCIH8Zas6aB3Bk_c5Rgi1PDtFQ6qVbF/view?usp=sharing
	Test file: https://drive.google.com/file/d/1CySGnd2OZKn73D2VlPbwtZHnCQPkcB1S/view?usp=sharing
	NIH Dataset is provided in train, val & test seperated files following a 70-10-20 split, such that there is no patient cross-over between training & test sets. 

	Model: 'ResNet_lr_0-0001.ipynb'
	The provided file 'ResNet_lr_0-0001.ipynb' is set up to be run independently in Google Colab (for GPU access).
	The results described in the summary paper are the output from a tuning process which involves the running of several such parallel models, each with a fixed different learning rate. 
	The file herein is fixed to a learning rate of 0.001. 

	Summary Paper: 
	The paper summarises the analysis and results.  
	
	
