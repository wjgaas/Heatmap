# Heatmap
Heatmap approach for Fashion AI keypoint

Preprocessing
1. split train to trainminusval and val

train
1. cd ./experiments/CPM_FPN/
2. python ./train_net

eval
1. cd ./evaluation
2. python ./csv_evaluation_FPN.py

experiments
1.  CPM  -> 23% on leaderboard
2.  CPM_ResNet 17.9% on valset
3.  CPM_FPN + data_aug -> 11% on valset, 12% on leaderboard

 
  
  
#---------------------------------------------- Related Papers--------------------------------------------------------------

1. Attentive Fashion Grammar Network for Fashion Landmark Detection and Clothing Category Classification (BIT, UCLA) - CVPR 2018
-  Worthy reading

2. Fashion Landmark Detection in the Wild (Sensetime) - ECCV 2016
-  Don't waste your time reading this paper, unless you want to learn from scratch


3. A Coarse-Fine Network for Keypoint Localization (U of Sydeny)  - ICCV 2017
-  Worthy reading. 非常有意思，文章有两个部分，第一个部分Coarse利用detection的方式检测潜在的目标区域，第二个部分利用softmax的方式分类点。
