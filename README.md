## Accepted by ICLR 2020: https://openreview.net/forum?id=S1e2agrFvS
# Geom-GCN: Geometric Graph Convolutional Networks
## Authors
### Hongbin Pei, Bingzhe Wei, Kevin Chen-Chuan Chang, Yu Lei, Bo Yang

GraphDML-UIUC-JLU: Graph-structured Data Mining and Machine Learning at University of Illinois at Urbana-Champaign (UIUC) and Jilin University (JLU)



### Abstract

Message-passing neural networks (MPNNs) have been successfully applied in a wide variety of applications in the real world. However, two fundamental weaknesses of MPNNs' aggregators limit their ability to represent graph-structured data: losing the structural information of nodes in neighborhoods and lacking the ability to capture long-range dependencies in disassortative graphs. Few studies have noticed the weaknesses from different perspectives. From the observations on classical neural network and network geometry, we propose a novel geometric aggregation scheme for graph neural networks to overcome the two weaknesses.  The behind basic idea is the aggregation on a graph can benefit from a continuous space underlying the graph. The proposed aggregation scheme is permutation-invariant and consists of three modules, node embedding, structural neighborhood, and bi-level aggregation. We also present an implementation of the scheme in graph convolutional networks, termed Geom-GCN, to perform transductive learning on graphs. Experimental results show the proposed Geom-GCN achieved state-of-the-art performance on a wide range of open datasets of graphs.

![](https://github.com/graphdml-uiuc-jlu/geom-gcn/blob/master/preview.PNG)

### Citing this Paper

If you find our paper and/or code useful in your research, please cite the following paper:

>@inproceedings{ICLR2020GeomGCN,  
> title={Geom-GCN: Geometric Graph Convolutional Networks},  
> author={Pei, Hongbin and Wei, Bingzhe and Chang, Kevin Chen-Chuan and Lei, Yu and Yang, Bo},  
> booktitle={International Conference on Learning Representations (ICLR)},  
> year={2020}  
>}  

## Code

#### Required Packages
1. PyTorch
2. NetworkX
3. Deep Graph Library https://www.dgl.ai/
4. Numpy
5. Scipy
6. Scikit-Learn
7. Tensorflow
8. TensorboardX https://github.com/lanpa/tensorboardX

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
