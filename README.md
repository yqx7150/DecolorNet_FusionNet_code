# DecolorNet_FusionNet_code
Variable Augmented Neural Network for Decolorization and Multi-Exposure Fusion

%% The Code is created based on the method described in the following paper:    
% [1] Q. Liu, H. Leung.“Variable Augmented Neural Network for Decolorization and Multi-Exposure Fusion”    
% Information Fusion, vol. 46, pp.114-127, 2019.    
% Author: Q. Liu, H. Leung    
% Date : 22/4/2017    
% Version : 1.0    
% The code and the algorithm are for non-comercial use only.    
% Copyright 2017, University of Calgary.   
% The current version is not optimized.    



# Flowchart of the DecolorNet architecture
![repeat-MDAEP](https://github.com/yqx7150/DecolorNet_FusionNet_code/blob/master/Flowchart%20demonstration%20of%20the%20proposed%20DecolorNet%20architecture.png) 
 
  
The whole method consists of the global-local contrast conversion stage and the image-gradient fusion stage. In the CNN procedure, both operators “Conv” and “ReLU” are included in the first and second layers, while only “Conv” exists in the third layer.   


## Demonstration of DecolorNet
![](./Compare_DecolorNet.png)  

## Demonstration of FusionNet
![](./Demonstration_FusionNet.png) 


## Other Related Projects
  * GcsDecolor: Gradient correlation similarity for efficient contrast preserving decolorization [<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/7088620)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/GcsDecolor)

  * Log-Euclidean Metrics for Contrast Preserving Decolorization
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/document/8016668)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/LeDecolor)

