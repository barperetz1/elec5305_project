# elec5305_project
### Repository structure
Main  
|____audioMNIST.ipynb (CNN classification model)  
|\_\_\_\_snnAudio1.ipynb (SNN classification model (train/test = 500/100))  
|\_\_\_\_snnAudio2.ipynb (SNN classification model (train/test = 1600/400))  
|\_\_\_\_jupyter_outputs (contains pdf versions of notebooks to save results if changes are made)  
     |\_\_\_\_CNN_results.pdf  
     |\_\_\_\_SNN_results_2.pdf  
     |\_\_\_\_SNN_results_2.pdf  
### Usage
* Download the audioMNIST dataset from "https://github.com/soerenab/AudioMNIST". Only download the 'data' directory and remove the file called 'audioMNIST_meta.txt'
* Select an experiment - Google Colab is recommended for devices that do not have a CUDA based GPU
* Fill in the path to the downloaded audioMNIST dataset
* Run each cell in the python notebook in order, if any changes are made run from the beginning
* Change only hyperparameter values or modify network architectures, keep in mind the input size to ensure the network is always compatible with the image.
