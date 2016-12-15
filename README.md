# About
This is an implementation of product name recognition using a Conditional Random Fields (CRF). It uses the command based CRFsuite as its base. 
# Feature (attribute) generation
	* Part-Of-Speech of the current word 
	* Part-Of-Speech of the next word
	* Part-Of-Speech of the previous word
	* The current word 
	* The previous word
	* The next word
	* The previous two word
	* The next two word
# Requirements (Libraries/Code)
	* nltk (used for its wrapper of the Stanford POS tagger)
	* Stanford POS tagger (must be downloaded and extracted somewhere)
	* CRFsuite: a fast implementation of Conditional Random Fields (CRFs)
	* Python 3.4 to run the feature extractor code (only tested on this version)
	* feature-extractor.py (a python code which used to extract the above mentioned feature) 
# Dataset 
The data we used is collected from the BuildDirect blog log file and partitioned 80% for training and 20% for testing purpose. Both the training and the testing raw data processed in a CRFsuite format which requires a data set in which an item line begins with its label, followed by its attributes separated by TAB ('\t') characters.
