# Geom-GCN: Geometric Graph Convolutional Networks

## Accepted by ICLR 2020: https://openreview.net/forum?id=S1e2agrFvS

If you find our paper and/or code useful in your research, please cite the following paper:

>@inproceedings{ICLR2020GeomGCN,  
> title={Geom-GCN: Geometric Graph Convolutional Networks},  
> author={Pei, Hongbin and Wei, Bingzhe and Chang, Kevin Chen-Chuan and Lei, Yu and Yang, Bo},  
> booktitle={International Conference on Learning Representations (ICLR)},  
> year={2020}  
>}  

#### Required Packages
PyTorch, NetworkX, DGL, Numpy, Scipy, Scikit-Learn, Tensorboard, TensorboardX

#### Table 3
To replicate the Geom-GCN results from Table 3, run
```bash
bash NewTableThreeGeomGCN_runs.txt
```
To replicate the GCN results from Table 3, run
```bash
bash NewTableThreeGCN_runs.txt
```
To replicate the GAT results from Table 3, run
```bash
bash NewTableThreeGAT_runs.txt
```

Results will be stored in `runs`.
#### Combination of Embedding Methods
To replicate the results for utilizing all embedding methods simultaneously, run
```bash
bash ExperimentTwoAllGeomGCN_runs.txt
```

Results will be stored in `runs`.
