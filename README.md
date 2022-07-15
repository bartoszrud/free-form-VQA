# free-form-VQA
From (question, short answer) pair to long answer.  

Put VQA annotations in the data folder (at the same level as code folder).

First run two notebook *rules.ipynb* and *image_captions.ipynb* to generate question-answer pairs from VQA2.0 and captions accordingly.   
Next, run notebook *Concat_datasets.ipynb* to produce the final dataset in json format. 

To be able to train OFA model you need to generate training and validation files in required format. To do this, run notebook *OFA_format.ipynb*. 

Results from OFA can be parsed and combined with ground truth answers using *OFA_result_parsing.ipynb* notebook.
