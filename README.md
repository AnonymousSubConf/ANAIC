#  Code For ANA-IC

## Require

- Python 3.9
- PyTorch 1.10.2
- dgl 0.7.2
- numpy  1.20.3

The  hyper-parameters for ANA-IC are as follows:
```python
python main.py --name_dataset cora --num_epochs 50 --pf 0.1 --pe 0.45 --lr2 1e-2 --wd2 1e-4 --K 1 --t 3 --lambd 100

python main.py --name_dataset pubmed --num_epochs 100 --pf 0.0 --pe 0.6 --lr2 1e-2 --wd2 1e-4  --K 3 --t -4 --lambd 280

python main.py --name_dataset citeseer --num_epochs 10 --num_layer 1 --pf 0.0 --pe 0.35 --lr2 1e-2 --wd2 1e-2  --K 2 --t 5 --lambd 30
```

