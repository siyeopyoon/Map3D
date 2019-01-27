April 2016 - September 2016

3D shapes matching implementation, based on "Continuous Matching via Vector Field Flow" Corman et al

|                  Option                    |   Values   |                                                                                                                                                                                                                                                                                                                                                                                                              Details                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Required |
|:------------------------------------------:|:----------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|---------:|
| -p PLATFORM_IDX<br>--platform PLATFORM_IDX | int [1-2]  | [1] Tensorflow, [2] Theano                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |    yes   |
|             -t TYPE_IDX<br>--type TYPE_IDX | int [1-2]  | [1] Breast cancer type classification<br>[2] Survival rate regression                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |    yes   |
|    -d DATASET_IDX<br>--dataset DATASET_IDX | int [1-15] | [1] DNA Methylation Platform GPL8490<br>[2] DNA Methylation Platform GPL16304<br>[3] Gene Expression Count<br>[4] Gene Expression FPKM<br>[5] Gene Expression FPKM-UQ<br>[6] miRNA Expression<br>[7] Gene Expression Count + miRNA Expression<br>[8] Gene Expression FPKM + miRNA Expression<br>[9] Gene Expression FPKM-UQ + miRNA Expression<br>[10] DNA Methylation Platform GPL8490 + Gene Expression Count + miRNA Expression<br>[11] DNA Methylation Platform GPL16304 + Gene Expression Count + miRNA Expression<br>[12] DNA Methylation Platform GPL8490 + Gene Expression FPKM + miRNA Expression<br>[13] DNA Methylation Platform GPL16304 + Gene Expression FPKM + miRNA Expression<br>[14] DNA Methylation Platform GPL8490 + Gene Expression FPKM-UQ + miRNA Expression<br>[15] DNA Methylation Platform GPL16304 + Gene Expression FPKM-UQ + miRNA Expression |    yes   |
|            --pretrain_epoch PRETRAIN_EPOCH | int        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |    no    |
|                   -train_epoch TRAIN_EPOCH | int        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |    no    |
|                    --batch_size BATCH_SIZE | int        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |    no    |
|                  --pretrain_lr PRETRAIN_LR | int        | Pre-training learning rate                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |    no    |
|                        --train_lr TRAIN_LR | int        | Training learning rate                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |    no    |
|                          --dropout DROPOUT | int        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |    no    |
|                              --pca PCA_IDX | int [1-2]  | [1] Use PCA<br>[2] Don't use PCA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |    no    |
|                  --optimizer OPTIMIZER_IDX | int [1-3]  | [1] Stochastic gradient descent<br>[2] RMSProp<br>[3] Adam                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |    no    |
