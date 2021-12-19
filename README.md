# CrossMMT_plus
  
## Requirement   
* Python 3.5 
* Pytorch 1.0.0 & torchvision 0.2.1
* numpy
* scipy 1.2.1 

## Data Preparation
- Download the pre-computed/pre-extracted data from [GoogleDrive](https://drive.google.com/drive/folders/1Nbx5Oa5746_uAcuRi73DmuhQhrxvrAc9?usp=sharing) and move them to ```data/processed``` folder. Or you can use the file ```dataset/preprocess.py``` to prepare your own data.
- *[Optional]* Download the pre-trained model weights from [GoogleDrive](https://drive.google.com/drive/folders/1LtTjWeGuLNvQYMTjdrYbdVjbxr7bLQQC?usp=sharing) and move them to ```pretrained_models``` folder.

## Training & Testing

training:  
```
sh scripts/train.sh  
```
Or testing:
```
sh scripts/test.sh  
```

## Contact

Shizhen Zhao: xbrainzsz@gmail.com
