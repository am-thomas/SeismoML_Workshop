# SeismoML_Workshop
Materials for Nemmers Workshop 2024: Machine Learning in Seismology

Session 1: [Google Colab](https://colab.research.google.com/drive/1GcgW-U959-ef0Ux1Z4JoZRq3RftG4L0L?usp=sharing)

## Installation 
* Download [Miniconda](https://docs.anaconda.com/free/miniconda/miniconda-install/) for your operating system if you do not have conda. You can skip the optional step 2 in the Miniconda download instructions.
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
conda install -c conda-forge obspy
pip install scikit-learn
pip install seisbench
pip install notebook
```
