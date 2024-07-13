# A3C-L4S


In this we plug A3C Model into L4S-AQM.

## Description

- ./Data collected for model learning/: This contains all the kernel logs from our routers.

- data_processing.ipynb : This file will process all the kernel logging data we get from our routers to specifically extract data about the network conditions of our L4S algorithm to use as Observation Space for our model.

- a3c_l4s.ipynb : This file trains the A3C model for 100 episodes and save the results in Training Results and Saed Training Data.

## Getting Started

Clone this repository first.

### Dependencies

* Python v3.9.13 or Higher

Libraries required:
* gym - v0.21.0
* tensorflow - v2.8.2
* keras - v2.8.0
* numpy - v1.23.3
* matplotlib -v3.5.2
* pandas - v1.4.4



### Installing

* Install python on your systems (Annaconda is easy to configure the versions of python and installed libraries)

OR

* You can upload files from "/Data collected for model learning" folder ,data_processing.ipynb and then a3c_l4s.ipynb  to google colab or  instead of the tedious process of uploading just use Jupyter notebooks on your device.

Then,

Install dependent libraries for running the python notebook.

### Executing program

* Execute Run all to execute both data_processing.ipynb and then a3c_l4s.ipynb



## Investigators

- Shiva Pokhrel <shiva.pokhrel@deakin.edu.au>
- Jonathan Kua <jonathan.kua@deakin.edu.au>
- Deol Satish <dsatish@deakin.edu.au>

## References


