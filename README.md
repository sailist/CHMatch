# CHMatch
Code of CVPR2023 paper Contrastive Hierarchical Matching and Robust Adaptive Threshold Boosted Semi-Supervised Learning

## Reimplement

Clone the repo contains CHMatch code and install requirements: 
```
git clone https://github.com/sailist/image-classification
cd image-classification
pip install -r requirements.txt
```

Run follow commands:
```
python scripts/semi/chmatch.py --dataset=cifar100
python scripts/semi/chmatch.py --dataset=cifar10
python scripts/semi/chmatch.py --dataset=stl10
```

These commands will print training commands.
