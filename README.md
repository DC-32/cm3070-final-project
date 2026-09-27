# cm3070-final-project



Code and outputs for my final project 

*Identifying research methodologies that are used in research in the computing disciplines* 



The project compares 
classical TF-IDF classification 
vs SciBERT classification 

to predict the field discipline and methodology 
in computing research publications




## Files

`Classical Classification.ipynb` - TF-IDF, Naive Bayes and Logistic Regression models and their final evaluation

`SciBERT Classification.ipynb` - SciBERT training, evaluation, comparison experiments and prediction functions

`Data` - the final datasets, saved partitions, supporting files used by both notebooks

`Results` - the saved metrics, predictions, confusion matrices and other outputs used in the final report

`Models` - the saved classical models and SciBERT configuration/tokenizer files



The final SciBERT `model.safetensors` files are not included in the repository 
as each is approx 430 MB in size
