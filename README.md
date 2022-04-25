# **An Improved Algorithm for Rare Cell-Type Detection Based on GiniClust3**



## Files included:

* **mainCode.ipynb** - containing the main code of our model (need to change the input file path)
* **1M_neurons_neuron20k.h5** - the input dataset we used (can be download from https://support.10xgenomics.com/single-cell-gene-expression/datasets/1.3.0/1M_neurons)
* **Final_Paper** - final project report
* Dataset - containing the input dataset we tried
* Simulate.ipynb - code for generating simulated dataset, 
  * `nGenes` : gene number
  * `batchCells`: cell number
  * `group.prob`: proportion of each cell population
* GiniClust3.ipynb - the code file for implementing GiniClust3 (used for the comparison with our model)

* desc.py, network.py, SAE.py (desc code download from https://github.com/eleozzr/desc, **Make sure they are in the same folder as the mainCode.py file**)

* Simulated_dataset - folder containing all the simulated dataset (with different proportion of rare cell)

* Result - containing output images and scores.

  

## Prerequisities

* giniclust3 (https://github.com/rdong08/GiniClust3)
  * Installation: `pip install giniclust3`
* desc (https://github.com/eleozzr/desc) (no need to install this package, just import SAE.py and network.py)
  * Installation: `pip install desc`
* leidenalg (https://github.com/vtraag/leidenalg)
  * Installation: `pip install leidenalg`
* Tensorflow 2*



## How to run the code

**Import the dataset you want to run with, and then run the code.**

>  Make sure the mainCode.ipynb, network.py and SAE.py are all in one folder

>  comment or delete the the code below if you run the code locally

```python
from google.colab import drive
drive.mount('/content/drive')
```





