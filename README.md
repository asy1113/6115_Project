# NLP Pulmonary Embolism 


### pe_pyContextNLP_pe.ipynb
PE NLP pipeline for training and testing. it contains functions including: 
* Save annotation dataframes to annotation files 
* Read ann file of selected document
* Convert annotations to dataframe
* Convert dataframe to Annotation instance
* Mention level evaluation

### dimer_pipe.ipynb
D-dimer NLP pipeline for training and testing. it contains similar functions as PE pipeline.

### depolyment.ipynb
Combined PE and d-dimer pipeline, and save the annotation results to output.csv.

### csv2modifier_rules.ipynb
Covert csv file format to PyContextNLP modifier_rules format.

### DocumentClassifier_pe.py
Modified DocumentClassifier.py.

### pynlp_pipe_pe.py
A wrapper of PyContextNLP using PyRush as the sentence segmenter. It return entity annotations, relationships and document classification. 

### pynlp_valid.py
This module is used for evaluation.


### pe_Simple_Classification_System.ipynb
New PE NLP pipeline for training, testing and deployment.
Output file: out_table.csv.

### dimer_pipe_v0002.ipynb
New d-dimer pipeline for training, testing and deployment.
Output file: out_table_dimer.csv.
