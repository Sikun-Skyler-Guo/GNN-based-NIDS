# GNN-NIDS TensorFlow implementation
Most of the code is adopted from https://github.com/BNN-UPC/GNN-NIDS
The concrete GNN architecture in encoded in the *GNN.py* file, meanwhile the whole model can be trained by simply executing the *main.py* file, as shown below.

```
    python main.py
```
Or you can run the *main.ipynb*, and we believe this option is better if parameter finetuning is needed.

```
# PATH of the training data
train: ./data/TRAIN

#PATH of the validation data
validation: ./data/VAL
```
