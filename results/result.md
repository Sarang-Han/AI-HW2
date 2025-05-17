## Experiment A: Basic model (Observe overfitting)
- run_experiment(dropout=False, use_aug=False, weight_decay=0.0)
- 정규화 기법을 사용하지 않은 기본 모델

```
[Epoch 1] Train Loss: 1.9190, Acc: 0.3016 | Test Loss: 1.9117, Acc: 0.2917
[Epoch 2] Train Loss: 1.6731, Acc: 0.3930 | Test Loss: 1.7352, Acc: 0.3552
[Epoch 3] Train Loss: 1.5378, Acc: 0.4470 | Test Loss: 1.6210, Acc: 0.4060
[Epoch 4] Train Loss: 1.4131, Acc: 0.4940 | Test Loss: 1.8592, Acc: 0.3413
[Epoch 5] Train Loss: 1.3603, Acc: 0.5058 | Test Loss: 1.5609, Acc: 0.4373
[Epoch 6] Train Loss: 1.2668, Acc: 0.5444 | Test Loss: 1.7093, Acc: 0.3794
[Epoch 7] Train Loss: 1.2114, Acc: 0.5636 | Test Loss: 1.4336, Acc: 0.4862
[Epoch 8] Train Loss: 1.1613, Acc: 0.5788 | Test Loss: 2.5357, Acc: 0.2979
[Epoch 9] Train Loss: 1.0932, Acc: 0.6096 | Test Loss: 1.6962, Acc: 0.3865
[Epoch 10] Train Loss: 1.0430, Acc: 0.6266 | Test Loss: 1.5885, Acc: 0.4352
[Epoch 11] Train Loss: 0.9983, Acc: 0.6538 | Test Loss: 2.4361, Acc: 0.3555
[Epoch 12] Train Loss: 0.9634, Acc: 0.6592 | Test Loss: 1.6711, Acc: 0.4570
[Epoch 13] Train Loss: 0.9077, Acc: 0.6932 | Test Loss: 1.5491, Acc: 0.4682
[Epoch 14] Train Loss: 0.8426, Acc: 0.7084 | Test Loss: 1.9302, Acc: 0.4450
[Epoch 15] Train Loss: 0.8218, Acc: 0.7120 | Test Loss: 1.6007, Acc: 0.4895
[Epoch 16] Train Loss: 0.7730, Acc: 0.7354 | Test Loss: 1.5469, Acc: 0.4786
[Epoch 17] Train Loss: 0.7206, Acc: 0.7574 | Test Loss: 1.6912, Acc: 0.4402
[Epoch 18] Train Loss: 0.6971, Acc: 0.7664 | Test Loss: 1.3249, Acc: 0.5359
[Epoch 19] Train Loss: 0.6366, Acc: 0.7946 | Test Loss: 1.4356, Acc: 0.5336
[Epoch 20] Train Loss: 0.6032, Acc: 0.7974 | Test Loss: 1.7097, Acc: 0.4963
[Epoch 21] Train Loss: 0.5504, Acc: 0.8248 | Test Loss: 1.5264, Acc: 0.5246
[Epoch 22] Train Loss: 0.5046, Acc: 0.8376 | Test Loss: 1.3271, Acc: 0.5538
[Epoch 23] Train Loss: 0.4845, Acc: 0.8452 | Test Loss: 1.5823, Acc: 0.4965
[Epoch 24] Train Loss: 0.4637, Acc: 0.8554 | Test Loss: 1.4681, Acc: 0.5284
[Epoch 25] Train Loss: 0.4241, Acc: 0.8730 | Test Loss: 1.6254, Acc: 0.5099
[Epoch 26] Train Loss: 0.4058, Acc: 0.8772 | Test Loss: 1.7736, Acc: 0.5092
[Epoch 27] Train Loss: 0.3687, Acc: 0.8898 | Test Loss: 1.9261, Acc: 0.4833
[Epoch 28] Train Loss: 0.3352, Acc: 0.9020 | Test Loss: 1.5647, Acc: 0.5247
[Epoch 29] Train Loss: 0.3182, Acc: 0.9084 | Test Loss: 1.8297, Acc: 0.4896
[Epoch 30] Train Loss: 0.2769, Acc: 0.9262 | Test Loss: 1.7270, Acc: 0.5065
```

## Experiment B: Dropout only
- run_experiment(dropout=True, use_aug=False, weight_decay=0.0)
- Dropout만 사용한 모델

```
[Epoch 1] Train Loss: 2.0366, Acc: 0.2456 | Test Loss: 1.9660, Acc: 0.2619
[Epoch 2] Train Loss: 1.8119, Acc: 0.3326 | Test Loss: 1.8600, Acc: 0.3308
[Epoch 3] Train Loss: 1.7187, Acc: 0.3564 | Test Loss: 1.6846, Acc: 0.3741
[Epoch 4] Train Loss: 1.6298, Acc: 0.3906 | Test Loss: 1.7016, Acc: 0.3713
[Epoch 5] Train Loss: 1.5538, Acc: 0.4276 | Test Loss: 1.5272, Acc: 0.4421
[Epoch 6] Train Loss: 1.5160, Acc: 0.4436 | Test Loss: 2.0726, Acc: 0.2842
[Epoch 7] Train Loss: 1.4730, Acc: 0.4524 | Test Loss: 2.1842, Acc: 0.3107
[Epoch 8] Train Loss: 1.4062, Acc: 0.4788 | Test Loss: 1.7305, Acc: 0.3696
[Epoch 9] Train Loss: 1.3932, Acc: 0.4936 | Test Loss: 1.4475, Acc: 0.4626
[Epoch 10] Train Loss: 1.3422, Acc: 0.5094 | Test Loss: 1.4660, Acc: 0.4560
[Epoch 11] Train Loss: 1.3121, Acc: 0.5174 | Test Loss: 1.3379, Acc: 0.5048
[Epoch 12] Train Loss: 1.2892, Acc: 0.5242 | Test Loss: 1.4091, Acc: 0.4838
[Epoch 13] Train Loss: 1.2257, Acc: 0.5512 | Test Loss: 1.3281, Acc: 0.5139
[Epoch 14] Train Loss: 1.2296, Acc: 0.5418 | Test Loss: 1.3700, Acc: 0.5089
[Epoch 15] Train Loss: 1.1890, Acc: 0.5664 | Test Loss: 1.4520, Acc: 0.4755
[Epoch 16] Train Loss: 1.1564, Acc: 0.5880 | Test Loss: 1.3059, Acc: 0.5104
[Epoch 17] Train Loss: 1.1498, Acc: 0.5846 | Test Loss: 1.4886, Acc: 0.4592
[Epoch 18] Train Loss: 1.1147, Acc: 0.5916 | Test Loss: 1.2758, Acc: 0.5352
[Epoch 19] Train Loss: 1.0763, Acc: 0.6086 | Test Loss: 1.4007, Acc: 0.4912
[Epoch 20] Train Loss: 1.0800, Acc: 0.6050 | Test Loss: 1.5628, Acc: 0.4481
[Epoch 21] Train Loss: 1.0189, Acc: 0.6256 | Test Loss: 1.7251, Acc: 0.4230
[Epoch 22] Train Loss: 1.0116, Acc: 0.6298 | Test Loss: 1.6919, Acc: 0.4553
[Epoch 23] Train Loss: 0.9748, Acc: 0.6472 | Test Loss: 1.4128, Acc: 0.5069
[Epoch 24] Train Loss: 0.9569, Acc: 0.6488 | Test Loss: 1.8267, Acc: 0.4448
[Epoch 25] Train Loss: 0.9444, Acc: 0.6630 | Test Loss: 1.3116, Acc: 0.5366
[Epoch 26] Train Loss: 0.9157, Acc: 0.6690 | Test Loss: 1.6815, Acc: 0.4547
[Epoch 27] Train Loss: 0.9055, Acc: 0.6726 | Test Loss: 1.3833, Acc: 0.5200
[Epoch 28] Train Loss: 0.8582, Acc: 0.6884 | Test Loss: 1.4026, Acc: 0.5050
[Epoch 29] Train Loss: 0.8465, Acc: 0.6940 | Test Loss: 1.3599, Acc: 0.5307
[Epoch 30] Train Loss: 0.8272, Acc: 0.6972 | Test Loss: 1.4886, Acc: 0.5187
```

## Experiment C: Data Augmentation only
- run_experiment(dropout=False, use_aug=True, weight_decay=0.0)
- Data Augmentation만 사용한 모델

```
[Epoch 1] Train Loss: 1.9667, Acc: 0.2608 | Test Loss: 1.8233, Acc: 0.3154
[Epoch 2] Train Loss: 1.7226, Acc: 0.3690 | Test Loss: 1.6898, Acc: 0.3679
[Epoch 3] Train Loss: 1.5955, Acc: 0.4134 | Test Loss: 2.3577, Acc: 0.2757
[Epoch 4] Train Loss: 1.5233, Acc: 0.4496 | Test Loss: 1.6891, Acc: 0.3887
[Epoch 5] Train Loss: 1.4514, Acc: 0.4704 | Test Loss: 2.2727, Acc: 0.3036
[Epoch 6] Train Loss: 1.3987, Acc: 0.4998 | Test Loss: 1.5289, Acc: 0.4392
[Epoch 7] Train Loss: 1.3496, Acc: 0.5140 | Test Loss: 1.6886, Acc: 0.4193
[Epoch 8] Train Loss: 1.3130, Acc: 0.5244 | Test Loss: 1.4796, Acc: 0.4591
[Epoch 9] Train Loss: 1.2844, Acc: 0.5452 | Test Loss: 1.7110, Acc: 0.4208
[Epoch 10] Train Loss: 1.2413, Acc: 0.5530 | Test Loss: 1.8486, Acc: 0.3874
[Epoch 11] Train Loss: 1.2176, Acc: 0.5604 | Test Loss: 1.6361, Acc: 0.4352
[Epoch 12] Train Loss: 1.1896, Acc: 0.5764 | Test Loss: 1.5247, Acc: 0.4658
[Epoch 13] Train Loss: 1.1919, Acc: 0.5826 | Test Loss: 2.7491, Acc: 0.3342
[Epoch 14] Train Loss: 1.1557, Acc: 0.5832 | Test Loss: 1.4800, Acc: 0.4927
[Epoch 15] Train Loss: 1.1154, Acc: 0.6134 | Test Loss: 1.3548, Acc: 0.5215
[Epoch 16] Train Loss: 1.1042, Acc: 0.6086 | Test Loss: 1.2777, Acc: 0.5453
[Epoch 17] Train Loss: 1.1005, Acc: 0.6072 | Test Loss: 1.3115, Acc: 0.5256
[Epoch 18] Train Loss: 1.0793, Acc: 0.6176 | Test Loss: 1.3910, Acc: 0.5082
[Epoch 19] Train Loss: 1.0650, Acc: 0.6212 | Test Loss: 1.3074, Acc: 0.5422
[Epoch 20] Train Loss: 1.0400, Acc: 0.6292 | Test Loss: 1.3863, Acc: 0.5122
[Epoch 21] Train Loss: 1.0274, Acc: 0.6318 | Test Loss: 1.3204, Acc: 0.5370
[Epoch 22] Train Loss: 1.0301, Acc: 0.6398 | Test Loss: 2.8344, Acc: 0.3143
[Epoch 23] Train Loss: 1.0057, Acc: 0.6420 | Test Loss: 1.4507, Acc: 0.5111
[Epoch 24] Train Loss: 1.0139, Acc: 0.6506 | Test Loss: 2.2421, Acc: 0.4133
[Epoch 25] Train Loss: 0.9982, Acc: 0.6558 | Test Loss: 1.2723, Acc: 0.5634
[Epoch 26] Train Loss: 0.9755, Acc: 0.6664 | Test Loss: 1.3594, Acc: 0.5387
[Epoch 27] Train Loss: 0.9635, Acc: 0.6610 | Test Loss: 1.2090, Acc: 0.5829
[Epoch 28] Train Loss: 0.9499, Acc: 0.6638 | Test Loss: 1.8077, Acc: 0.4652
[Epoch 29] Train Loss: 0.9529, Acc: 0.6620 | Test Loss: 1.1170, Acc: 0.6032
[Epoch 30] Train Loss: 0.9266, Acc: 0.6780 | Test Loss: 1.3725, Acc: 0.5414
```


## Experiment D: Dropout + Augmentation + Weight Decay
- run_experiment(dropout=True, use_aug=True, weight_decay=1e-4)
- 세가지 정규화 기법을 모두 적용한 모델

```
[Epoch 1] Train Loss: 2.0836, Acc: 0.2120 | Test Loss: 1.9369, Acc: 0.2758
[Epoch 2] Train Loss: 1.8831, Acc: 0.2974 | Test Loss: 1.7985, Acc: 0.3039
[Epoch 3] Train Loss: 1.7817, Acc: 0.3246 | Test Loss: 1.8219, Acc: 0.3032
[Epoch 4] Train Loss: 1.7129, Acc: 0.3478 | Test Loss: 1.7327, Acc: 0.3329
[Epoch 5] Train Loss: 1.6628, Acc: 0.3628 | Test Loss: 1.7583, Acc: 0.3771
[Epoch 6] Train Loss: 1.6038, Acc: 0.4022 | Test Loss: 1.5694, Acc: 0.4177
[Epoch 7] Train Loss: 1.5750, Acc: 0.4182 | Test Loss: 2.1744, Acc: 0.2593
[Epoch 8] Train Loss: 1.5517, Acc: 0.4268 | Test Loss: 1.6340, Acc: 0.3907
[Epoch 9] Train Loss: 1.5335, Acc: 0.4310 | Test Loss: 1.6518, Acc: 0.3865
[Epoch 10] Train Loss: 1.4932, Acc: 0.4530 | Test Loss: 1.4095, Acc: 0.4877
[Epoch 11] Train Loss: 1.4578, Acc: 0.4644 | Test Loss: 1.4817, Acc: 0.4466
[Epoch 12] Train Loss: 1.4436, Acc: 0.4734 | Test Loss: 1.4863, Acc: 0.4563
[Epoch 13] Train Loss: 1.4377, Acc: 0.4724 | Test Loss: 1.4872, Acc: 0.4674
[Epoch 14] Train Loss: 1.4171, Acc: 0.4766 | Test Loss: 1.5744, Acc: 0.4287
[Epoch 15] Train Loss: 1.3982, Acc: 0.4890 | Test Loss: 1.3728, Acc: 0.5045
[Epoch 16] Train Loss: 1.3987, Acc: 0.4902 | Test Loss: 1.4266, Acc: 0.4716
[Epoch 17] Train Loss: 1.3739, Acc: 0.5068 | Test Loss: 1.6139, Acc: 0.4311
[Epoch 18] Train Loss: 1.3656, Acc: 0.5068 | Test Loss: 1.5941, Acc: 0.4306
[Epoch 19] Train Loss: 1.3348, Acc: 0.5090 | Test Loss: 1.4767, Acc: 0.4683
[Epoch 20] Train Loss: 1.3138, Acc: 0.5194 | Test Loss: 1.3142, Acc: 0.5208
[Epoch 21] Train Loss: 1.3025, Acc: 0.5300 | Test Loss: 1.2804, Acc: 0.5282
[Epoch 22] Train Loss: 1.2882, Acc: 0.5334 | Test Loss: 1.5320, Acc: 0.4533
[Epoch 23] Train Loss: 1.2763, Acc: 0.5334 | Test Loss: 1.9842, Acc: 0.3687
[Epoch 24] Train Loss: 1.2634, Acc: 0.5376 | Test Loss: 1.3090, Acc: 0.5093
[Epoch 25] Train Loss: 1.2704, Acc: 0.5422 | Test Loss: 1.6749, Acc: 0.4478
[Epoch 26] Train Loss: 1.2428, Acc: 0.5514 | Test Loss: 1.5022, Acc: 0.4768
[Epoch 27] Train Loss: 1.2526, Acc: 0.5522 | Test Loss: 1.4346, Acc: 0.4838
[Epoch 28] Train Loss: 1.2462, Acc: 0.5552 | Test Loss: 1.3869, Acc: 0.5022
[Epoch 29] Train Loss: 1.2231, Acc: 0.5570 | Test Loss: 1.3945, Acc: 0.4978
[Epoch 30] Train Loss: 1.2157, Acc: 0.5564 | Test Loss: 1.2873, Acc: 0.5360
```


## Experiment E: Weight Decay only (추가)
- run_experiment(dropout=False, use_aug=False, weight_decay=1e-4)
- Weight decay만 적용한 모델

```
[Epoch 1] Train Loss: 1.8925, Acc: 0.3160 | Test Loss: 1.7647, Acc: 0.3402
[Epoch 2] Train Loss: 1.6417, Acc: 0.3982 | Test Loss: 1.6201, Acc: 0.4042
[Epoch 3] Train Loss: 1.5202, Acc: 0.4450 | Test Loss: 1.5657, Acc: 0.4087
[Epoch 4] Train Loss: 1.4142, Acc: 0.4872 | Test Loss: 1.6840, Acc: 0.3998
[Epoch 5] Train Loss: 1.3285, Acc: 0.5232 | Test Loss: 1.5655, Acc: 0.4269
[Epoch 6] Train Loss: 1.2689, Acc: 0.5432 | Test Loss: 1.5793, Acc: 0.4365
[Epoch 7] Train Loss: 1.2070, Acc: 0.5782 | Test Loss: 1.6672, Acc: 0.3976
[Epoch 8] Train Loss: 1.1444, Acc: 0.5912 | Test Loss: 2.5780, Acc: 0.3068
[Epoch 9] Train Loss: 1.0991, Acc: 0.6068 | Test Loss: 1.3235, Acc: 0.5180
[Epoch 10] Train Loss: 1.0326, Acc: 0.6280 | Test Loss: 1.5586, Acc: 0.4573
[Epoch 11] Train Loss: 0.9973, Acc: 0.6440 | Test Loss: 1.4001, Acc: 0.5106
[Epoch 12] Train Loss: 0.9627, Acc: 0.6612 | Test Loss: 1.4605, Acc: 0.4895
[Epoch 13] Train Loss: 0.9001, Acc: 0.6878 | Test Loss: 1.4015, Acc: 0.5157
[Epoch 14] Train Loss: 0.8528, Acc: 0.6960 | Test Loss: 1.3694, Acc: 0.4971
[Epoch 15] Train Loss: 0.7947, Acc: 0.7272 | Test Loss: 1.3230, Acc: 0.5325
[Epoch 16] Train Loss: 0.7620, Acc: 0.7378 | Test Loss: 1.9103, Acc: 0.4307
[Epoch 17] Train Loss: 0.7211, Acc: 0.7528 | Test Loss: 1.5213, Acc: 0.4901
[Epoch 18] Train Loss: 0.6968, Acc: 0.7648 | Test Loss: 1.4423, Acc: 0.5117
[Epoch 19] Train Loss: 0.6480, Acc: 0.7864 | Test Loss: 1.3961, Acc: 0.5320
[Epoch 20] Train Loss: 0.5958, Acc: 0.8010 | Test Loss: 1.3366, Acc: 0.5502
[Epoch 21] Train Loss: 0.5529, Acc: 0.8292 | Test Loss: 2.3333, Acc: 0.4071
[Epoch 22] Train Loss: 0.5308, Acc: 0.8252 | Test Loss: 1.5204, Acc: 0.5096
[Epoch 23] Train Loss: 0.4558, Acc: 0.8614 | Test Loss: 1.8744, Acc: 0.4629
[Epoch 24] Train Loss: 0.4378, Acc: 0.8624 | Test Loss: 3.3271, Acc: 0.3573
[Epoch 25] Train Loss: 0.4145, Acc: 0.8696 | Test Loss: 1.8462, Acc: 0.4858
[Epoch 26] Train Loss: 0.3653, Acc: 0.8934 | Test Loss: 1.6156, Acc: 0.5250
[Epoch 27] Train Loss: 0.3387, Acc: 0.9020 | Test Loss: 2.0711, Acc: 0.4444
[Epoch 28] Train Loss: 0.3482, Acc: 0.8974 | Test Loss: 1.5227, Acc: 0.5309
[Epoch 29] Train Loss: 0.2751, Acc: 0.9304 | Test Loss: 1.5278, Acc: 0.5470
[Epoch 30] Train Loss: 0.2785, Acc: 0.9226 | Test Loss: 1.8650, Acc: 0.5083
```

---
2가지 조합만 사용하기

## Experiment F: Dropout + Data Augmentation
- run_experiment(dropout=True, use_aug=True, weight_decay=0.0)

```
[Epoch 1] Train Loss: 1.8925, Acc: 0.3160 | Test Loss: 1.7647, Acc: 0.3402
[Epoch 2] Train Loss: 1.6417, Acc: 0.3982 | Test Loss: 1.6201, Acc: 0.4042
[Epoch 3] Train Loss: 1.5202, Acc: 0.4450 | Test Loss: 1.5657, Acc: 0.4087
[Epoch 4] Train Loss: 1.4142, Acc: 0.4872 | Test Loss: 1.6840, Acc: 0.3998
[Epoch 5] Train Loss: 1.3285, Acc: 0.5232 | Test Loss: 1.5655, Acc: 0.4269
[Epoch 6] Train Loss: 1.2689, Acc: 0.5432 | Test Loss: 1.5793, Acc: 0.4365
[Epoch 7] Train Loss: 1.2070, Acc: 0.5782 | Test Loss: 1.6672, Acc: 0.3976
[Epoch 8] Train Loss: 1.1444, Acc: 0.5912 | Test Loss: 2.5780, Acc: 0.3068
[Epoch 9] Train Loss: 1.0991, Acc: 0.6068 | Test Loss: 1.3235, Acc: 0.5180
[Epoch 10] Train Loss: 1.0326, Acc: 0.6280 | Test Loss: 1.5586, Acc: 0.4573
[Epoch 11] Train Loss: 0.9973, Acc: 0.6440 | Test Loss: 1.4001, Acc: 0.5106
[Epoch 12] Train Loss: 0.9627, Acc: 0.6612 | Test Loss: 1.4605, Acc: 0.4895
[Epoch 13] Train Loss: 0.9001, Acc: 0.6878 | Test Loss: 1.4015, Acc: 0.5157
[Epoch 14] Train Loss: 0.8528, Acc: 0.6960 | Test Loss: 1.3694, Acc: 0.4971
[Epoch 15] Train Loss: 0.7947, Acc: 0.7272 | Test Loss: 1.3230, Acc: 0.5325
[Epoch 16] Train Loss: 0.7620, Acc: 0.7378 | Test Loss: 1.9103, Acc: 0.4307
[Epoch 17] Train Loss: 0.7211, Acc: 0.7528 | Test Loss: 1.5213, Acc: 0.4901
[Epoch 18] Train Loss: 0.6968, Acc: 0.7648 | Test Loss: 1.4423, Acc: 0.5117
[Epoch 19] Train Loss: 0.6480, Acc: 0.7864 | Test Loss: 1.3961, Acc: 0.5320
[Epoch 20] Train Loss: 0.5958, Acc: 0.8010 | Test Loss: 1.3366, Acc: 0.5502
[Epoch 21] Train Loss: 0.5529, Acc: 0.8292 | Test Loss: 2.3333, Acc: 0.4071
[Epoch 22] Train Loss: 0.5308, Acc: 0.8252 | Test Loss: 1.5204, Acc: 0.5096
[Epoch 23] Train Loss: 0.4558, Acc: 0.8614 | Test Loss: 1.8744, Acc: 0.4629
[Epoch 24] Train Loss: 0.4378, Acc: 0.8624 | Test Loss: 3.3271, Acc: 0.3573
[Epoch 25] Train Loss: 0.4145, Acc: 0.8696 | Test Loss: 1.8462, Acc: 0.4858
[Epoch 26] Train Loss: 0.3653, Acc: 0.8934 | Test Loss: 1.6156, Acc: 0.5250
[Epoch 27] Train Loss: 0.3387, Acc: 0.9020 | Test Loss: 2.0711, Acc: 0.4444
[Epoch 28] Train Loss: 0.3482, Acc: 0.8974 | Test Loss: 1.5227, Acc: 0.5309
[Epoch 29] Train Loss: 0.2751, Acc: 0.9304 | Test Loss: 1.5278, Acc: 0.5470
[Epoch 30] Train Loss: 0.2785, Acc: 0.9226 | Test Loss: 1.8650, Acc: 0.5083
```

## Experiment G: Data Augmentation + Weight Decay
- run_experiment(dropout=False, use_aug=True, weight_decay=1e-4)

```
[Epoch 1] Train Loss: 1.9660, Acc: 0.2664 | Test Loss: 1.8420, Acc: 0.3017
[Epoch 2] Train Loss: 1.7450, Acc: 0.3538 | Test Loss: 1.9098, Acc: 0.3071
[Epoch 3] Train Loss: 1.6543, Acc: 0.3888 | Test Loss: 1.6677, Acc: 0.3787
[Epoch 4] Train Loss: 1.5638, Acc: 0.4302 | Test Loss: 1.6593, Acc: 0.3786
[Epoch 5] Train Loss: 1.5009, Acc: 0.4454 | Test Loss: 1.6684, Acc: 0.4054
[Epoch 6] Train Loss: 1.4348, Acc: 0.4810 | Test Loss: 1.5632, Acc: 0.4352
[Epoch 7] Train Loss: 1.3958, Acc: 0.4850 | Test Loss: 3.7655, Acc: 0.2130
[Epoch 8] Train Loss: 1.3393, Acc: 0.5138 | Test Loss: 1.8629, Acc: 0.4045
[Epoch 9] Train Loss: 1.3052, Acc: 0.5312 | Test Loss: 1.4906, Acc: 0.4546
[Epoch 10] Train Loss: 1.3000, Acc: 0.5314 | Test Loss: 1.5200, Acc: 0.4456
[Epoch 11] Train Loss: 1.2410, Acc: 0.5522 | Test Loss: 1.5571, Acc: 0.4454
[Epoch 12] Train Loss: 1.2169, Acc: 0.5612 | Test Loss: 1.5146, Acc: 0.4744
[Epoch 13] Train Loss: 1.1976, Acc: 0.5696 | Test Loss: 2.1772, Acc: 0.3891
[Epoch 14] Train Loss: 1.1881, Acc: 0.5734 | Test Loss: 1.5177, Acc: 0.4912
[Epoch 15] Train Loss: 1.1702, Acc: 0.5820 | Test Loss: 1.4711, Acc: 0.4757
[Epoch 16] Train Loss: 1.1495, Acc: 0.5954 | Test Loss: 2.1242, Acc: 0.3811
[Epoch 17] Train Loss: 1.1241, Acc: 0.6002 | Test Loss: 1.6623, Acc: 0.4468
[Epoch 18] Train Loss: 1.0940, Acc: 0.6138 | Test Loss: 1.3204, Acc: 0.5435
[Epoch 19] Train Loss: 1.0766, Acc: 0.6138 | Test Loss: 1.3706, Acc: 0.5258
[Epoch 20] Train Loss: 1.0763, Acc: 0.6212 | Test Loss: 1.4408, Acc: 0.5194
[Epoch 21] Train Loss: 1.0696, Acc: 0.6222 | Test Loss: 1.2360, Acc: 0.5580
[Epoch 22] Train Loss: 1.0255, Acc: 0.6348 | Test Loss: 1.5249, Acc: 0.4933
[Epoch 23] Train Loss: 1.0235, Acc: 0.6366 | Test Loss: 1.2747, Acc: 0.5631
[Epoch 24] Train Loss: 1.0135, Acc: 0.6376 | Test Loss: 1.6549, Acc: 0.4938
[Epoch 25] Train Loss: 0.9939, Acc: 0.6468 | Test Loss: 1.3123, Acc: 0.5604
[Epoch 26] Train Loss: 0.9782, Acc: 0.6490 | Test Loss: 1.3240, Acc: 0.5505
[Epoch 27] Train Loss: 0.9795, Acc: 0.6564 | Test Loss: 1.2829, Acc: 0.5534
[Epoch 28] Train Loss: 0.9892, Acc: 0.6474 | Test Loss: 1.4263, Acc: 0.5203
[Epoch 29] Train Loss: 0.9654, Acc: 0.6570 | Test Loss: 1.1525, Acc: 0.5995
[Epoch 30] Train Loss: 0.9212, Acc: 0.6776 | Test Loss: 1.4319, Acc: 0.5267
```

## Experiment H: Dropout + Weight Decay
- run_experiment(dropout=True, use_aug=False, weight_decay=1e-4)

```
[Epoch 1] Train Loss: 2.0411, Acc: 0.2356 | Test Loss: 1.8626, Acc: 0.3056
[Epoch 2] Train Loss: 1.8225, Acc: 0.3192 | Test Loss: 1.7415, Acc: 0.3558
[Epoch 3] Train Loss: 1.7350, Acc: 0.3474 | Test Loss: 1.7655, Acc: 0.3675
[Epoch 4] Train Loss: 1.6480, Acc: 0.3880 | Test Loss: 1.6328, Acc: 0.4111
[Epoch 5] Train Loss: 1.5807, Acc: 0.4144 | Test Loss: 1.5409, Acc: 0.4280
[Epoch 6] Train Loss: 1.5300, Acc: 0.4344 | Test Loss: 1.5361, Acc: 0.4609
[Epoch 7] Train Loss: 1.4833, Acc: 0.4568 | Test Loss: 1.6665, Acc: 0.3838
[Epoch 8] Train Loss: 1.4179, Acc: 0.4760 | Test Loss: 1.5220, Acc: 0.4230
[Epoch 9] Train Loss: 1.3926, Acc: 0.4912 | Test Loss: 1.6020, Acc: 0.4081
[Epoch 10] Train Loss: 1.3492, Acc: 0.4966 | Test Loss: 1.4704, Acc: 0.4684
[Epoch 11] Train Loss: 1.3051, Acc: 0.5212 | Test Loss: 1.4326, Acc: 0.4641
[Epoch 12] Train Loss: 1.2834, Acc: 0.5290 | Test Loss: 1.3044, Acc: 0.5121
[Epoch 13] Train Loss: 1.2387, Acc: 0.5480 | Test Loss: 1.5243, Acc: 0.4752
[Epoch 14] Train Loss: 1.2346, Acc: 0.5508 | Test Loss: 1.3925, Acc: 0.4894
[Epoch 15] Train Loss: 1.1779, Acc: 0.5756 | Test Loss: 1.4941, Acc: 0.4490
[Epoch 16] Train Loss: 1.1626, Acc: 0.5752 | Test Loss: 1.3510, Acc: 0.5138
[Epoch 17] Train Loss: 1.1288, Acc: 0.5896 | Test Loss: 1.4018, Acc: 0.5108
[Epoch 18] Train Loss: 1.0923, Acc: 0.5936 | Test Loss: 1.9853, Acc: 0.4032
[Epoch 19] Train Loss: 1.0779, Acc: 0.6026 | Test Loss: 1.4188, Acc: 0.4931
[Epoch 20] Train Loss: 1.0239, Acc: 0.6282 | Test Loss: 1.5855, Acc: 0.4565
[Epoch 21] Train Loss: 1.0230, Acc: 0.6276 | Test Loss: 1.3067, Acc: 0.5148
[Epoch 22] Train Loss: 1.0068, Acc: 0.6414 | Test Loss: 1.6040, Acc: 0.4695
[Epoch 23] Train Loss: 0.9692, Acc: 0.6492 | Test Loss: 1.2314, Acc: 0.5560
[Epoch 24] Train Loss: 0.9359, Acc: 0.6654 | Test Loss: 1.4729, Acc: 0.5028
[Epoch 25] Train Loss: 0.9353, Acc: 0.6586 | Test Loss: 1.6966, Acc: 0.4630
[Epoch 26] Train Loss: 0.9074, Acc: 0.6790 | Test Loss: 1.5249, Acc: 0.5018
[Epoch 27] Train Loss: 0.8614, Acc: 0.6856 | Test Loss: 1.3572, Acc: 0.5180
[Epoch 28] Train Loss: 0.8413, Acc: 0.6942 | Test Loss: 1.2618, Acc: 0.5530
[Epoch 29] Train Loss: 0.8100, Acc: 0.7154 | Test Loss: 1.2796, Acc: 0.5395
[Epoch 30] Train Loss: 0.8679, Acc: 0.6886 | Test Loss: 1.2368, Acc: 0.5601
```
