# Fine-Tuning CodeT5

## Introduction

In our implementation of this assignment, we use a fine-tuned CodeT5 
Transformer model (from Hugging Face) in order to automatically recommend 
potential if statements contained within Python functions. Specifically, 
we used a small version of CodeT5, codet5-small, and trained it on a set 
of data (ft_train.csv) provided by our professor.

## Running our Model

Our implementation can be found in "CodeT5.ipynb".

If you would like to run the model in a way that doesn't take a large 
amount of time, please uncomment this small section of code in the cell
labeled "#2. Load Dataset".

```
#train = train[:2000]
#val = val[:100]
#test = test[:100]
```

If you would like to use our trained model for your own purposes, it is
saved at this line:
```
trainer.save_model("t5_Model")
```
Stop execution at this point in the file.
