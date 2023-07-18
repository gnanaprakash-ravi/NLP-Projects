# CHAII - Hindi and Tamil Question Answering

This contains the code for the result obtained using XLM-RoBERTa on the chaii dataset.

## Dataset:

The chaii-dataset is used for fine-tuning, along with mlqa (MultiLingual Question Answering) and XQuAD (Cross-lingual Question Answering Dataset) datasets on the XLM-RoBERTa model that has been pre-trained on SQuAD2.
The Chaii dataset consists of the following:

id: unique id for each example
context: a paragraph based on which the questions have to be answered
question: the question that has to be answered
answer_start: the index from which the answer starts (only in the train set)
answer_text: the answer in string format (only in the train set)


## Models:

The model which is used is XLM-RoBERTa.

## Result:

XLM-RoBERTa (pre-trained on squadv2, finetuned with mlqa, xquad, chaii) gives 0.616 jaccord score
