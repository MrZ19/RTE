# RTE

## Related information
<!--Here is the code of "Self-supervised rigid transformation equivariance for accurate 3D point cloud registration" (``https://www.sciencedirect.com/science/article/pii/S0031320322002655``), which proposes a rigid transformation equivarance for point cloud rigistration.-->
Here is the RTE code.
<!--Note: the code is being prepared. -->

## Implementation
The code is tested with Pytorch 1.6.0 with CUDA 10.2.89. Prerequisites include scipy, h5py, tqdm, etc. Your can install them by yourself.

The ModelNet40 dataset can be download from:
```
https://github.com/WangYueFt/dcp
```

Start training with the command:
```
python main.py 
```

Start testing with the command:
```
python main.py --eval True --mdoel_path YOUR_CHECKPOINT_DIRECTORY
```

## Acknowledgement
The code is insipred by DCP, PRNet, RPMNet, etc.
<!--
## Please cite:
```
@ARTICLE{zhang_rte_pr_2022,
  title={Self-supervised rigid transformation equivariance for accurate 3D point cloud registration},
  author={Zhiyuan Zhang and Jiadai Sun and Yuchao Dai and Dingfu Zhou and Xibin Song and Mingyi He},
  journal={Pattern Recognition},
  volume    = {130},
  pages     = {108784},
  year      = {2022}}
```
-->
