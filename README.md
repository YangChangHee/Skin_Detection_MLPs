# Skin_Detection_MLPs
Skin-detection(Using GCN)
## Copyright / End User License
* SFA (Skin-nonSkin dataset) - Citation : CASATI, J. P. B. ; MORAES, D. R. ; RODRIGUES, E. L. L. . SFA: A Human Skin Image Database based on FERET and AR Facial Images. In: IX Workshop de Visão Computacional, 2013, Rio de Janeiro. Anais do VIII Workshop de Visão Computacional, 2013.
* If you want to use this Dataset, go to URL : http://www.sel.eesc.usp.br/sfa/ (I don`t upload the SFA file Because it could be a problem)
* I am currently writting a paper with this code, If it is completed, I will also post my thesis
* If you use it commercially, please contact my email, If you use it in github or other open source in a project, please provide a source.
## Contact Information
* qazw5741@naver.com & YangChangHee2251@gamil.com
## Installation Process
* openCV
* numpy
* matplotlib
* pandas
* tqdm
* pytorch
* hashlib
* json
* os
* torchvision
* argparse
* seaborn
## Directions for use
* Step 1. Data load (https://github.com/YangChangHee/Skin_Detection_MLPs/blob/main/Make_dataset/Step.1%20Data%20load.ipynb)

Image Convert SFA_Skin.npy and SFA_NonSkin.npy

* Step 2. Data_Make (https://github.com/YangChangHee/Skin_Detection_MLPs/blob/main/Make_dataset/Step.2%20Data_Make.ipynb)

Image RGB Convert RGBCbCr(5-dimention)

Visualize NonSkin dataset and Skin dataset (Graph x axis : Cb, y axis : Cr)

save npy file (SFA_Skin_RGBCBCR.npy, SFA_NSkin_RGBCBCR.npy)

![graph](https://user-images.githubusercontent.com/59610723/113128625-f594a600-9254-11eb-8cf1-d1050e0e0a75.png)

* Step 3. Model(https://github.com/YangChangHee/Skin_Detection_MLPs/blob/main/Define_Model/Step.3%20Model.ipynb)

Use Adam, ReLU, MLPs

Hid_dim_1 =[3, 4, 5, 6], Hid_dim_2 =[3, 4, 5, 6]

Result

![11](https://user-images.githubusercontent.com/59610723/113129314-b6b32000-9255-11eb-8133-b084bcd09e0a.png)
![22](https://user-images.githubusercontent.com/59610723/113129338-bd419780-9255-11eb-8cae-3676317673ad.png)
![33](https://user-images.githubusercontent.com/59610723/113129344-be72c480-9255-11eb-8d8a-c9ca65fe8d0f.png)


