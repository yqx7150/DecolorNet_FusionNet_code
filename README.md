# DecolorNet_FusionNet_code
Variable Augmented Neural Network for Decolorization and Multi-Exposure Fusion

% Code is created based on the method described in the following paper:    
% Q. Liu, H. Leung.“Variable Augmented Neural Network for Decolorization and Multi-Exposure Fusion”    
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

## Introduction of Wallpaper Dataset
These wallpaper images contain a variety of important structures such as large scale edges, smooth areas and fine textures, etc. Particularly, the average size of the dataset is 1254×1881, which is much larger than those of Cadik dataset and CSDD dataset. The average sizes of Cadik dataset and CSDD dataset are 292×352 and 356×406, respectively. The large size makes the conversion to be much more difficult than the Cadik dataset and CSDD dataset. It contains greater color complexity. The full collection of the dataset appears in the sub-folder of "Wallpapers_Dataset". 
![](./Wallpapers_Dataset/Wallpapers_Dataset.png)     

## Other Related Projects
  * GcsDecolor: Gradient Correlation Similarity for Efficient Contrast Preserving Decolorization [<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/7088620)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/GcsDecolor)   [<font size=5>**[Slide]**</font>](https://github.com/yqx7150/EDAEPRec/tree/master/Slide)

  * Log-Euclidean Metrics for Contrast Preserving Decolorization
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/document/8016668)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/LeDecolor)

  * Semiparametric Decolorization With Laplacian-Based Perceptual Quality Metric
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/document/7456206)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/SPDecolor)

  * Color-to-gray Conversion on Wallpaper Dataset
[<font size=5>**[Dataset]**</font>](https://github.com/yqx7150/DecolorNet_FusionNet_code/tree/master/Wallpapers_Dataset)   
  
  * Variable Augmented Network for Invertible Modality Synthesis-Fusion
[<font size=5>**[Paper]**</font>](https://arxiv.org/ftp/arxiv/papers/2109/2109.00670.pdf)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/iVAN)
 
 * Variable augmentation network for invertible MR coil compression
[<font size=5>**[Paper]**</font>](https://www.sciencedirect.com/science/article/abs/pii/S0730725X24000225)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/VAN-ICC)         

 * Virtual coil augmentation for MR coil extrapoltion via deep learning
[<font size=5>**[Paper]**</font>](https://www.sciencedirect.com/science/article/abs/pii/S0730725X22001722)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/VCA)    

  * Variable Augmented Network for Invertible Decolorization (基于辅助变量增强的可逆彩色图像灰度化)
[<font size=5>**[Paper]**</font>](https://jeit.ac.cn/cn/article/doi/10.11999/JEIT221205?viewType=HTML)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/VA-IDN)        

  * Invertible and Variable Augmented Network for Pretreatment Patient-Specific Quality Assurance Dose Prediction  [<font size=5>**[Paper]**</font>](https://link.springer.com/article/10.1007/s10278-023-00930-w)       
    
  * Temporal Image Sequence Separation in Dual-tracer Dynamic PET with an Invertible Network  [<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/10542421)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/DTS-INN)        
