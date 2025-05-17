## 실험 A
- 기본 베이스라인 모델

```
Configuration: Dropout=False, Aug=False, Weight Decay=0.0
[Epoch 1] Train Loss: 1.8385, Acc: 0.3272 | Test Loss: 1.6921, Acc: 0.3634
[Epoch 2] Train Loss: 1.5767, Acc: 0.4298 | Test Loss: 1.5364, Acc: 0.4416
[Epoch 3] Train Loss: 1.4658, Acc: 0.4680 | Test Loss: 1.5855, Acc: 0.4134
[Epoch 4] Train Loss: 1.3756, Acc: 0.5050 | Test Loss: 1.5670, Acc: 0.4345
[Epoch 5] Train Loss: 1.2920, Acc: 0.5428 | Test Loss: 1.6355, Acc: 0.4419
[Epoch 6] Train Loss: 1.2185, Acc: 0.5714 | Test Loss: 1.5959, Acc: 0.4404
[Epoch 7] Train Loss: 1.1433, Acc: 0.6034 | Test Loss: 1.3628, Acc: 0.4982
[Epoch 8] Train Loss: 1.1039, Acc: 0.6152 | Test Loss: 1.2868, Acc: 0.5370
[Epoch 9] Train Loss: 1.0546, Acc: 0.6368 | Test Loss: 1.4443, Acc: 0.4979
[Epoch 10] Train Loss: 1.0019, Acc: 0.6468 | Test Loss: 1.3994, Acc: 0.5191
[Epoch 11] Train Loss: 0.9515, Acc: 0.6684 | Test Loss: 2.2098, Acc: 0.3847
[Epoch 12] Train Loss: 0.9201, Acc: 0.6906 | Test Loss: 1.1793, Acc: 0.5798
[Epoch 13] Train Loss: 0.9041, Acc: 0.6898 | Test Loss: 1.2054, Acc: 0.5748
[Epoch 14] Train Loss: 0.8706, Acc: 0.6998 | Test Loss: 1.2495, Acc: 0.5686
[Epoch 15] Train Loss: 0.8214, Acc: 0.7136 | Test Loss: 1.4273, Acc: 0.4983
[Epoch 16] Train Loss: 0.7817, Acc: 0.7356 | Test Loss: 1.2342, Acc: 0.5585
[Epoch 17] Train Loss: 0.7473, Acc: 0.7458 | Test Loss: 1.3670, Acc: 0.5628
[Epoch 18] Train Loss: 0.7172, Acc: 0.7592 | Test Loss: 1.3043, Acc: 0.5481
[Epoch 19] Train Loss: 0.7082, Acc: 0.7522 | Test Loss: 1.1171, Acc: 0.6045
[Epoch 20] Train Loss: 0.6725, Acc: 0.7790 | Test Loss: 1.9749, Acc: 0.4551
[Epoch 21] Train Loss: 0.6689, Acc: 0.7728 | Test Loss: 1.6072, Acc: 0.5167
[Epoch 22] Train Loss: 0.6198, Acc: 0.7964 | Test Loss: 1.0535, Acc: 0.6362
[Epoch 23] Train Loss: 0.6086, Acc: 0.7918 | Test Loss: 1.1393, Acc: 0.6202
[Epoch 24] Train Loss: 0.5684, Acc: 0.8102 | Test Loss: 1.2698, Acc: 0.5942
[Epoch 25] Train Loss: 0.5426, Acc: 0.8274 | Test Loss: 1.3523, Acc: 0.5716
[Epoch 26] Train Loss: 0.5394, Acc: 0.8256 | Test Loss: 1.3400, Acc: 0.5768
[Epoch 27] Train Loss: 0.4978, Acc: 0.8398 | Test Loss: 1.0756, Acc: 0.6386
[Epoch 28] Train Loss: 0.4822, Acc: 0.8482 | Test Loss: 1.4948, Acc: 0.5289
[Epoch 29] Train Loss: 0.4755, Acc: 0.8440 | Test Loss: 1.3708, Acc: 0.5675
[Epoch 30] Train Loss: 0.4229, Acc: 0.8724 | Test Loss: 1.1416, Acc: 0.6297
```

## 실험 B
- 드롭아웃만 적용 모델
```
Configuration: Dropout=True, Aug=False, Weight Decay=0.0
[Epoch 1] Train Loss: 1.9781, Acc: 0.2626 | Test Loss: 1.7760, Acc: 0.3617
[Epoch 2] Train Loss: 1.7345, Acc: 0.3600 | Test Loss: 1.6131, Acc: 0.4147
[Epoch 3] Train Loss: 1.6180, Acc: 0.3918 | Test Loss: 1.5800, Acc: 0.4305
[Epoch 4] Train Loss: 1.5354, Acc: 0.4358 | Test Loss: 1.5236, Acc: 0.4544
[Epoch 5] Train Loss: 1.4671, Acc: 0.4644 | Test Loss: 1.4497, Acc: 0.4774
[Epoch 6] Train Loss: 1.4077, Acc: 0.4812 | Test Loss: 1.4224, Acc: 0.4942
[Epoch 7] Train Loss: 1.4005, Acc: 0.4928 | Test Loss: 1.6015, Acc: 0.4308
[Epoch 8] Train Loss: 1.3594, Acc: 0.5080 | Test Loss: 1.3903, Acc: 0.5087
[Epoch 9] Train Loss: 1.3237, Acc: 0.5218 | Test Loss: 2.7929, Acc: 0.2901
[Epoch 10] Train Loss: 1.2981, Acc: 0.5306 | Test Loss: 1.3080, Acc: 0.5307
[Epoch 11] Train Loss: 1.2575, Acc: 0.5462 | Test Loss: 1.6986, Acc: 0.4082
[Epoch 12] Train Loss: 1.2276, Acc: 0.5590 | Test Loss: 1.4527, Acc: 0.4790
[Epoch 13] Train Loss: 1.1999, Acc: 0.5652 | Test Loss: 1.4267, Acc: 0.5050
[Epoch 14] Train Loss: 1.1860, Acc: 0.5710 | Test Loss: 1.3172, Acc: 0.5327
[Epoch 15] Train Loss: 1.1617, Acc: 0.5776 | Test Loss: 1.2365, Acc: 0.5578
[Epoch 16] Train Loss: 1.1480, Acc: 0.5914 | Test Loss: 1.5485, Acc: 0.4611
[Epoch 17] Train Loss: 1.1162, Acc: 0.5960 | Test Loss: 1.4385, Acc: 0.4946
[Epoch 18] Train Loss: 1.0777, Acc: 0.6138 | Test Loss: 1.1365, Acc: 0.6005
[Epoch 19] Train Loss: 1.0754, Acc: 0.6126 | Test Loss: 1.2881, Acc: 0.5373
[Epoch 20] Train Loss: 1.0537, Acc: 0.6206 | Test Loss: 1.2421, Acc: 0.5675
[Epoch 21] Train Loss: 1.0439, Acc: 0.6270 | Test Loss: 1.2933, Acc: 0.5450
[Epoch 22] Train Loss: 1.0271, Acc: 0.6258 | Test Loss: 1.3977, Acc: 0.5333
[Epoch 23] Train Loss: 0.9911, Acc: 0.6444 | Test Loss: 1.1288, Acc: 0.5947
[Epoch 24] Train Loss: 0.9832, Acc: 0.6534 | Test Loss: 1.2830, Acc: 0.5460
[Epoch 25] Train Loss: 0.9778, Acc: 0.6502 | Test Loss: 1.2910, Acc: 0.5591
[Epoch 26] Train Loss: 0.9586, Acc: 0.6674 | Test Loss: 1.1570, Acc: 0.5892
[Epoch 27] Train Loss: 0.9416, Acc: 0.6684 | Test Loss: 1.3554, Acc: 0.5283
[Epoch 28] Train Loss: 0.9474, Acc: 0.6618 | Test Loss: 1.2378, Acc: 0.5675
[Epoch 29] Train Loss: 0.9016, Acc: 0.6830 | Test Loss: 1.1570, Acc: 0.5917
[Epoch 30] Train Loss: 0.8924, Acc: 0.6808 | Test Loss: 1.1187, Acc: 0.6071
```

## 실험 C
- 데이터 증강만 적용 모델
```
Configuration: Dropout=False, Aug=True, Weight Decay=0.0
[Epoch 1] Train Loss: 1.9191, Acc: 0.2962 | Test Loss: 1.7872, Acc: 0.3576
[Epoch 2] Train Loss: 1.7015, Acc: 0.3746 | Test Loss: 1.9287, Acc: 0.3485
[Epoch 3] Train Loss: 1.5879, Acc: 0.4014 | Test Loss: 1.6039, Acc: 0.4173
[Epoch 4] Train Loss: 1.5029, Acc: 0.4560 | Test Loss: 1.5503, Acc: 0.4350
[Epoch 5] Train Loss: 1.4113, Acc: 0.4972 | Test Loss: 1.5161, Acc: 0.4364
[Epoch 6] Train Loss: 1.3603, Acc: 0.5118 | Test Loss: 1.6671, Acc: 0.4227
[Epoch 7] Train Loss: 1.2988, Acc: 0.5320 | Test Loss: 1.3969, Acc: 0.4968
[Epoch 8] Train Loss: 1.2533, Acc: 0.5466 | Test Loss: 1.5182, Acc: 0.4789
[Epoch 9] Train Loss: 1.2353, Acc: 0.5652 | Test Loss: 1.2953, Acc: 0.5343
[Epoch 10] Train Loss: 1.1798, Acc: 0.5832 | Test Loss: 1.7377, Acc: 0.4359
[Epoch 11] Train Loss: 1.1424, Acc: 0.5980 | Test Loss: 1.2984, Acc: 0.5376
[Epoch 12] Train Loss: 1.1045, Acc: 0.6128 | Test Loss: 1.4073, Acc: 0.5212
[Epoch 13] Train Loss: 1.0927, Acc: 0.6098 | Test Loss: 1.3760, Acc: 0.5281
[Epoch 14] Train Loss: 1.0592, Acc: 0.6312 | Test Loss: 1.3373, Acc: 0.5496
[Epoch 15] Train Loss: 1.0456, Acc: 0.6332 | Test Loss: 1.2412, Acc: 0.5585
[Epoch 16] Train Loss: 1.0263, Acc: 0.6390 | Test Loss: 1.3889, Acc: 0.5219
[Epoch 17] Train Loss: 1.0289, Acc: 0.6298 | Test Loss: 2.6495, Acc: 0.3963
[Epoch 18] Train Loss: 0.9932, Acc: 0.6480 | Test Loss: 1.3965, Acc: 0.5401
[Epoch 19] Train Loss: 1.0023, Acc: 0.6480 | Test Loss: 1.1588, Acc: 0.5960
[Epoch 20] Train Loss: 0.9757, Acc: 0.6548 | Test Loss: 1.3664, Acc: 0.5529
[Epoch 21] Train Loss: 0.9510, Acc: 0.6582 | Test Loss: 1.1920, Acc: 0.5881
[Epoch 22] Train Loss: 0.9270, Acc: 0.6760 | Test Loss: 1.5338, Acc: 0.5142
[Epoch 23] Train Loss: 0.9343, Acc: 0.6680 | Test Loss: 1.2409, Acc: 0.5838
[Epoch 24] Train Loss: 0.9163, Acc: 0.6736 | Test Loss: 1.2578, Acc: 0.5846
[Epoch 25] Train Loss: 0.8736, Acc: 0.6916 | Test Loss: 1.4278, Acc: 0.5478
[Epoch 26] Train Loss: 0.8869, Acc: 0.6814 | Test Loss: 1.0621, Acc: 0.6289
[Epoch 27] Train Loss: 0.8723, Acc: 0.7042 | Test Loss: 1.1624, Acc: 0.6102
[Epoch 28] Train Loss: 0.8584, Acc: 0.6952 | Test Loss: 1.5646, Acc: 0.5273
[Epoch 29] Train Loss: 0.8273, Acc: 0.7046 | Test Loss: 1.1136, Acc: 0.6193
[Epoch 30] Train Loss: 0.8335, Acc: 0.7012 | Test Loss: 1.6515, Acc: 0.5267
```

## 실험 D
- 드롭아웃 + 데이터 증강 + 가중치 감소 적용 모델
```
Configuration: Dropout=True, Aug=True, Weight Decay=0.0001
[Epoch 1] Train Loss: 2.0030, Acc: 0.2494 | Test Loss: 1.7969, Acc: 0.3481
[Epoch 2] Train Loss: 1.7794, Acc: 0.3298 | Test Loss: 1.9056, Acc: 0.3203
[Epoch 3] Train Loss: 1.6993, Acc: 0.3598 | Test Loss: 1.5971, Acc: 0.4158
[Epoch 4] Train Loss: 1.6437, Acc: 0.3936 | Test Loss: 1.6662, Acc: 0.3862
[Epoch 5] Train Loss: 1.6039, Acc: 0.3972 | Test Loss: 1.5568, Acc: 0.4271
[Epoch 6] Train Loss: 1.5456, Acc: 0.4306 | Test Loss: 1.4597, Acc: 0.4677
[Epoch 7] Train Loss: 1.5101, Acc: 0.4398 | Test Loss: 1.5258, Acc: 0.4485
[Epoch 8] Train Loss: 1.4624, Acc: 0.4590 | Test Loss: 1.5263, Acc: 0.4518
[Epoch 9] Train Loss: 1.4328, Acc: 0.4738 | Test Loss: 1.5248, Acc: 0.4676
[Epoch 10] Train Loss: 1.3869, Acc: 0.4962 | Test Loss: 1.3594, Acc: 0.5056
[Epoch 11] Train Loss: 1.3526, Acc: 0.5092 | Test Loss: 1.7948, Acc: 0.4276
[Epoch 12] Train Loss: 1.3815, Acc: 0.5010 | Test Loss: 1.4785, Acc: 0.4824
[Epoch 13] Train Loss: 1.3368, Acc: 0.5158 | Test Loss: 1.7555, Acc: 0.4032
[Epoch 14] Train Loss: 1.3068, Acc: 0.5208 | Test Loss: 1.3026, Acc: 0.5300
[Epoch 15] Train Loss: 1.2896, Acc: 0.5400 | Test Loss: 1.3474, Acc: 0.5112
[Epoch 16] Train Loss: 1.2771, Acc: 0.5370 | Test Loss: 1.6038, Acc: 0.4493
[Epoch 17] Train Loss: 1.2455, Acc: 0.5494 | Test Loss: 1.8614, Acc: 0.4165
[Epoch 18] Train Loss: 1.2604, Acc: 0.5450 | Test Loss: 1.3776, Acc: 0.5281
[Epoch 19] Train Loss: 1.2465, Acc: 0.5534 | Test Loss: 1.2895, Acc: 0.5410
[Epoch 20] Train Loss: 1.2186, Acc: 0.5628 | Test Loss: 1.4266, Acc: 0.4975
[Epoch 21] Train Loss: 1.2031, Acc: 0.5562 | Test Loss: 1.2241, Acc: 0.5518
[Epoch 22] Train Loss: 1.1837, Acc: 0.5780 | Test Loss: 1.2696, Acc: 0.5429
[Epoch 23] Train Loss: 1.1725, Acc: 0.5696 | Test Loss: 1.3814, Acc: 0.5184
[Epoch 24] Train Loss: 1.1664, Acc: 0.5856 | Test Loss: 1.2948, Acc: 0.5383
[Epoch 25] Train Loss: 1.1476, Acc: 0.5932 | Test Loss: 1.7392, Acc: 0.4492
[Epoch 26] Train Loss: 1.1593, Acc: 0.5882 | Test Loss: 1.5951, Acc: 0.4691
[Epoch 27] Train Loss: 1.1225, Acc: 0.5962 | Test Loss: 1.3308, Acc: 0.5471
[Epoch 28] Train Loss: 1.1151, Acc: 0.5968 | Test Loss: 1.4096, Acc: 0.5257
[Epoch 29] Train Loss: 1.1208, Acc: 0.6080 | Test Loss: 1.2134, Acc: 0.5606
[Epoch 30] Train Loss: 1.1218, Acc: 0.5966 | Test Loss: 1.1815, Acc: 0.5865
```