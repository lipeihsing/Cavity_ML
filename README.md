See FwdPredictor.ipynb for forward predictor.  
See InvDesigner.ipynb for inverse designer.  
Each notebook contains the module importing cell, several Torch.nn model class cells, a Torch.nn Dataset class cell, train and test function def cells, and a main cell for defining hyper-parameters, number of epoches, and performing training. The subsequent cells are for evaluation and data exporting.  
To create and use new model, insert a new cell to define a model class, then change the "model = <myModel(arg1, arg2, ...)>" command in the main scripting cell. Remember to check the input and output assignment in Dataset class to match either forward or inverse model training.  
  
Dataset and backup link:  
field_data.csv: 10000x45  
control_voltage.csv: 10000x24  
https://1drv.ms/u/s!Ar9kh_wdIvDu2jCMUVM-fBi2GW7p?e=w5WBcY  
  
Presentation slides (draft):  
https://1drv.ms/p/s!Ar9kh_wdIvDu2jaGJIhPc_AsTCMJ?e=tkmIG3  
