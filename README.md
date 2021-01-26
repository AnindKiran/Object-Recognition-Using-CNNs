<div align="center">
<img src = "https://github.com/AnindKiran/Object-Recognition-Using-CNNs/blob/master/cifar-10.png" width = "5%" height = "5%">
</div>

# Object-Recognition-Using-CNNs

#### Project 1 in a series of small projects designed to practice practical Machine Learning. 

This project is an implementation of the 2015 ICLR paper, "Striving For Simplicity: The All Convolutional Net". <br>
The link for the paper is : https://arxiv.org/pdf/1412.6806.pdf <br/>

The dataset used can be found on the following link : <a> https://www.cs.toronto.edu/~kriz/cifar.html </a> 

### Cloning the repo
```sh
git clone https://github.com/AnindKiran/Object-Recognition-Using-CNNs
cd Object-Recognition-Using-CNNs
```

### Prerequisites libraries

It is presumed that you have at least Python 3.7. 
The prerequisites include: Keras API, numpy, Matplotlib, PIL (now updated to Pillow but preferable to use PIL with this repo). Although using conda would be preferable, the following commands use pip to install libraries considering most users have the 'pip' utility. Use the following commands to install them: 
```sh
pip install Keras
pip install numpy
pip install matplotlib
```

### Using the notebook
Open Jupyter Notebook using the following command on the cmd / terminal (depending on your platform): 
```
jupyter notebook
```

The notebook will be visible for you to use. 

> NOTE : The pretrained model is available in this repo, in the file "all_cnn_weights_0.9088_0.4994.hdf5"
