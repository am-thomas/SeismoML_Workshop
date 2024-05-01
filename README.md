# SeismoML_Workshop
Materials for Nemmers Workshop 2024: Machine Learning in Seismology

## Installation 
* Download [Miniconda](https://docs.anaconda.com/free/miniconda/miniconda-install/) for your operating system. You can skip the optional step 2.
* Open Terminal (Mac/Linux) or the Anaconda Prompt (Windows). Create a new conda environment by running the following command 
```
conda create -n nemmers python=3.10
```
* Activate the new conda environment as follows: 
```
conda activate nemmers
```
* Install required packages (obspy, scikit-learn, seisbench, and jupyter notebook) and their dependencies 
```
conda install conda-forge::obspy
conda install conda-forge::scikit-learn
pip install seisbench
pip install notebook
```
