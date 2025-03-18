# **Quantum Krylov-subsapce method based linear solver**
### This is the numerical simulation code for [the paper](https://arxiv.org/abs/2405.06359v1)
## Structure

['data.txt'](data.txt) is the file wich contains the data of matrices used in the our code, and ['ISING_INSPIRED_H.ipynb'](ISING_INSPIRED_H.ipynb) provides a function to bulid matrices(actually, you could have matrices with different structures). 

Our main code consists of three main parts:

1,The [`QKSL.ipynb`](QKSL.ipynb) file is to show the QKSL under ideally condition;

2,The [`Childs.ipynb`](Childs.ipynb) file is to show the Fourier approach under ideally condition.

3,The [`variant_Hadamard_test.ipynb`](variant_Hadamard_test.ipynb) is to show the novel approach(i.e. a variant Hadamard-Test).


## Dependencies

$\bullet$ numpy == 1.26.3

$\bullet$ pennylane == 0.34.0

$\bullet$ scipy ==1.11.4
