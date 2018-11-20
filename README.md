# Show bounding boxes and labels
I added codes for showing the bounding boxes and labels. To show it, I used Jupyter Notebook and created deployer.ipynb and visualize_cg.ipynb files.

- Directory Structure  
```Shell
    |__ examples					
        |__ crestedgecko
        	|__ deployer.ipynb
        	|__ visualize_cg.ipynb
            	|__ train
            		|__ annotations
            			|__ CG_train2018_000000000001_patternless_0.png
            			|__ instances_crestedgecko_train2018
            		|__ crestedgecko_train2018
            			|__ CG_train2018_000000000001.jpg
        |__ shapes
        	|__ ...	        
```
- [deployer.ipynb](https://github.com/asyncbridge/pycococreator/blob/master/examples/crestedgecko/deployer.ipynb)  
1) Rename and resize image files.  
2) Create an annotation file from images and masking images.    
- [visualize_cg.ipynb](https://github.com/asyncbridge/pycococreator/blob/master/examples/crestedgecko/visualize_cg.ipynb)  
  
Show bounding boxes and labels including segmentations from the created annotation file.  
![alt text](https://github.com/asyncbridge/pycococreator/blob/master/examples/crestedgecko/output_6_0.png "output")

# pycococreator

pycococreator is a set of tools to help create [COCO](http://cocodataset.org) datasets. It includes functions to generate annotations in uncompressed RLE ("crowd") and polygons in the format COCO requires.

Read more here https://patrickwasp.com/create-your-own-coco-style-dataset/

![alt text](https://i.imgur.com/iQSPjeC.png "input files")
![alt text](https://i.imgur.com/py2aYK9.png "output")

# Install

`pip install git+git://github.com/waspinator/pycococreator.git@0.2.0`  
