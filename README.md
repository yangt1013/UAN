# Few shot ship recognition based on universal attention relationnet
## Requirement
python 3.6

Pytorch >=1.1

torchvision >=0.4

## Training

1. Download datatsets for GLPM (e.g. MAR-ships, CIB-ships, game-of-ships etc) and organize the structure as follows:
```bash
dataset

└── images
    |      ├── 1.jpg    
    |      ├── 2.jp
    |      └── ...    
    |      ├── n-1.jpg
    |      ├── n.jpg
└── train.csv
└── test.csv
```
2、Train from scratch with `train.py`.
## Citation
Please cite our paper if you use GLPM in your work.
```bash
@InProceedings{du2021fine,
  title={Few shot ship recognition based on universal attention relationnet},
  author={Hao Meng; Yang Tian; Yuting Sun; Tao Li},
  booktitle = {Chinese Journal of Scientific Instrument},
  year={2021}
}
```
