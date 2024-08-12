# **Enhancing K-Centres Algorithm Efficiency in Python across Multi-Core and Many-Core Platforms**
>The programs are part of a shor paper presented to a 18CCC.
>
>The site shows different implementation in python using: multithreading libraries for CPU and differents python libraries for execute K-Centres in GPU.
>
>These programs was develop by Santiago Monroy Heredia (smonroyh@unal.edu.co).

## Table of Contents
- [Python programs description](#Python)
- [Data set](#Data)
- [Installation and Usage](#Installation)
- [Contributing](#contributing)
- [License](#license)


## Python programs description

> ### Secuencial.ipynb: This notebook contains a sequential version of the k-centres algorithm. You can enhance this by optimizing the algorithm itself or using parallelization techniques.

> ### Evaluar_t_cpuParalelo.ipynb: Program that contains a multithreading version of K-Centres algorithm in Python.

> ### Evaluar_t_PyCUDA.ipynb: Program that contains a GPU parallel implementation of K-Centres algorithm using PyCUDA libaries.

> ### Evaluar_t_CUPY.ipynb: Program that contains a GPU parallel implementation of K-Centres algorithm using CUPY libaries.
	
> ### Evaluar_t_Numba.ipynb: Program that contains a GPU parallel implementation of K-Centres algorithm using Numba libaries .
	
## Data set
> ### Yataros1.csv: The CSV file contains 3012 objects, each with 40 acoustic indices. The number 3012 represents the total files, while 40 corresponds to the number of columns in the dataset.
By applying the K-Centres algorithm to the dataset Yataros1.csv. We aim to identify the most representative acoustic indices of the Yataros forest. Although this aspect is not the core focus of the article, the algorithm enables us to select K centers and subsequently determine which indices are most representative. Algorithm accelerations allow us to perform multiple executions in a fast elapsed time, enabling data analysis.

## Installation and Usage

The following files are developed in python using a google colab notebook.


> for PyCUDA: pip install pycuda
> for Numba: pip install numba
> for Cupy: pip install cupy-cuda11x

## Contributing
This site presents the implementation of four distinct parallelization strategies for the K-Centres algorithm parallelized in python with differents libraries for CPU (multithreading) and GPU (Cupy, Numba and PyCUDA). 
We evaluate their performance in terms of execution time while also considering some qualitative aspects, such as the complexity of each implementation and ease of use on many-core and multi-core architectures.

## License

