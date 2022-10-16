# CSCI662 HW2
I have implemented a feed-forward neural network from scratch and also using the PyTorch library. The main purpose of this assignment is to compare both implementations performance and accuracy. 

# Datasets
I trained each of these models on four datasets. These are located in the datasets folder.

# Embedding Files
I used embedding files to help with the featurizations for these models. This assignment has three embedding files name glove.6B.50d.txt fasttetxt.wiki.300d.vec and ufvytar.100d.txt

# Train Models
To train the implementation that was created from scratch you may use ```python train.py -u {hidden units} -l {learning rate} -f {max sequence length} -b {atch size} -e {epochs} -E {embedding file} -i {input file} -o {name of output model}``` and for the implementation using PyTorch you may use  ```python train-torch.py -u {hidden units} -l {learning rate} -f {max sequence length} -b {atch size} -e {epochs} -E {embedding file} -i {input file} -o {name of output model}```

# Classify Models
To classify text using the implementation that was made from scratch you may use  ```python classify.py -m {name of model} -i {input file} -o {name of output file}``` and ```python classify-torch.py -m {name of model} -i {input file} -o {name of output file}``` for the PyTorch implementation
