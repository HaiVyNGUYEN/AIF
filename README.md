# AIF
├── __Data__: all the data are stored in this folder
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;└── __Number__ (for example, Number=1205)
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;├── __Number__ (for example, Number=1205)  
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;├── __Number__ (for example, Number=1205)
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;└── __Number__ (for example, Number=1205)
├── __structure.py__: defining the architecture of the neural net   
└── __train.py__: training model    
### Preliminary step: set up virtual environment to work with python
Create a virtual environment:
```
conda create --name AIF python==3.7.12 -c conda-forge
```
Notice that the environment here is named AIF, you can choose a name at your convenience.

To work in this environment, we need to activate it: 
```
conda activate AIF
```
Now this environment is empty. We load packages/libraries necessary for our project:
```
pip install -r requirements.txt
```
