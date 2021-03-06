# snn
Code for training probabilistic binary and WTA SNNs using PyTorch.
Part of this code has been used for the following works:

N. Skatchkovsky, H. Jang, and O. Simeone, Federated Neuromorphic Learning of Spiking Neural Networks for Low-Power Edge Intelligence, accepted to IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP), 2020.
https://arxiv.org/abs/1910.09594

H. Jang, N. Skatchkovsky, and O. Simeone, VOWEL: A Local Online Learning Rule for Recurrent Networks of Probabilistic Spiking Winner-Take-All Circuits, to be presented at ICPR 2020
https://arxiv.org/abs/2004.09416

N. Skatchkovsky, H. Jang, and O. Simeone, End-to-End Learning of Neuromorphic Wireless Systems for Low-Power Edge Artificial Intelligence, to be presented at Asilomar 2020
https://arxiv.org/abs/2009.01527

# Installing 
This code can now be installed as a package and is meant to be shared in pip.
To clone and install locally the package, run 
~~~
git clone https://github.com/kclip/snn 
cd snn/ 
python -m pip install -e . 
~~~

# Run example
An experiment can be run on the MNIST-DVS dataset by launching

`python snn/launch_experiment.py`

Make sure to first download and preprocess the MNIST-DVS dataset using the script in `snn/data_preprocessing/process_mnistdvs.py` and change your home directory in `snn/launch_experiment.py`.
