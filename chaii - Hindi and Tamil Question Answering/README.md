# CHAII - Hindi and Tamil Question Answering

#### This contains the code for the result obtained using XLM-RoBERTa on chaii dataset.

## Dataset:

#### The chaii-dataset is used for fine-tuning, along with mlqa (MultiLingual Question Answering) and XQuAD (Cross-lingual Question Answering Dataset) datasets on the XLM-RoBERTa model that has been pre-trained on SQuAD2.
#### The chaii dataset consists of:
#### ==id==  : unique id for each examples
#### ==context== : a paragraph based on which the questions has to be answered
#### ==question==    : the question that has to be answered
#### ==answer_start==    : the index from which the answer starts (only in train set)
#### ==answer_text==     : the answer in string format (only in train set)
<div style="background-color: #ffffcc; padding: 10px;"></div>

## Models:

#### The model which is used are XLM-RoBERTa.

## Result:

#### XLM-RoBERTa (pretrained on squadv2, finetuned with mlqa, xquad, chaii) gives 0.616 jaccord score