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

---
## 드롭아웃 실험 - B와 비교

1. Dropout(0.3)
```
Configuration: Dropout=True, Aug=False, Weight Decay=0.0
[Epoch 1] Train Loss: 1.9066, Acc: 0.2984 | Test Loss: 1.7179, Acc: 0.3736
[Epoch 2] Train Loss: 1.6704, Acc: 0.3892 | Test Loss: 1.6411, Acc: 0.3971
[Epoch 3] Train Loss: 1.5628, Acc: 0.4310 | Test Loss: 1.6237, Acc: 0.3933
[Epoch 4] Train Loss: 1.4947, Acc: 0.4516 | Test Loss: 1.5145, Acc: 0.4508
[Epoch 5] Train Loss: 1.4171, Acc: 0.4916 | Test Loss: 1.5937, Acc: 0.4217
[Epoch 6] Train Loss: 1.3543, Acc: 0.5054 | Test Loss: 1.5007, Acc: 0.4654
[Epoch 7] Train Loss: 1.3123, Acc: 0.5288 | Test Loss: 1.4186, Acc: 0.4748
[Epoch 8] Train Loss: 1.2683, Acc: 0.5514 | Test Loss: 1.6685, Acc: 0.4167
[Epoch 9] Train Loss: 1.2141, Acc: 0.5566 | Test Loss: 1.5487, Acc: 0.4651
[Epoch 10] Train Loss: 1.1819, Acc: 0.5754 | Test Loss: 1.3015, Acc: 0.5278
[Epoch 11] Train Loss: 1.1424, Acc: 0.5970 | Test Loss: 1.2796, Acc: 0.5342
[Epoch 12] Train Loss: 1.0901, Acc: 0.6080 | Test Loss: 1.1791, Acc: 0.5772
[Epoch 13] Train Loss: 1.0906, Acc: 0.6092 | Test Loss: 1.3673, Acc: 0.5194
[Epoch 14] Train Loss: 1.0562, Acc: 0.6176 | Test Loss: 1.4353, Acc: 0.4860
[Epoch 15] Train Loss: 1.0268, Acc: 0.6414 | Test Loss: 1.2661, Acc: 0.5433
[Epoch 16] Train Loss: 1.0037, Acc: 0.6424 | Test Loss: 1.1420, Acc: 0.5874
[Epoch 17] Train Loss: 0.9655, Acc: 0.6614 | Test Loss: 1.1441, Acc: 0.5824
[Epoch 18] Train Loss: 0.9759, Acc: 0.6610 | Test Loss: 1.6990, Acc: 0.4352
[Epoch 19] Train Loss: 0.9516, Acc: 0.6608 | Test Loss: 1.0939, Acc: 0.6062
[Epoch 20] Train Loss: 0.9143, Acc: 0.6728 | Test Loss: 1.1922, Acc: 0.5833
[Epoch 21] Train Loss: 0.8894, Acc: 0.6862 | Test Loss: 1.1451, Acc: 0.5915
[Epoch 22] Train Loss: 0.8761, Acc: 0.6814 | Test Loss: 1.2190, Acc: 0.5703
[Epoch 23] Train Loss: 0.8659, Acc: 0.6952 | Test Loss: 1.2898, Acc: 0.5563
[Epoch 24] Train Loss: 0.8300, Acc: 0.7040 | Test Loss: 1.3443, Acc: 0.5561
[Epoch 25] Train Loss: 0.8249, Acc: 0.7038 | Test Loss: 1.1649, Acc: 0.6113
[Epoch 26] Train Loss: 0.7991, Acc: 0.7122 | Test Loss: 1.2374, Acc: 0.5779
[Epoch 27] Train Loss: 0.7859, Acc: 0.7162 | Test Loss: 1.3492, Acc: 0.5294
[Epoch 28] Train Loss: 0.7668, Acc: 0.7284 | Test Loss: 1.2480, Acc: 0.5783
[Epoch 29] Train Loss: 0.7461, Acc: 0.7348 | Test Loss: 1.1545, Acc: 0.5998
[Epoch 30] Train Loss: 0.7672, Acc: 0.7298 | Test Loss: 1.2486, Acc: 0.5729
```

2. Dropout(0.7)
```
[Epoch 1] Train Loss: 2.0909, Acc: 0.2314 | Test Loss: 1.8018, Acc: 0.3622
[Epoch 2] Train Loss: 1.8422, Acc: 0.3158 | Test Loss: 1.6918, Acc: 0.3980
[Epoch 3] Train Loss: 1.7446, Acc: 0.3452 | Test Loss: 1.5963, Acc: 0.4207
[Epoch 4] Train Loss: 1.6545, Acc: 0.3794 | Test Loss: 1.6246, Acc: 0.3973
[Epoch 5] Train Loss: 1.6112, Acc: 0.4012 | Test Loss: 1.8462, Acc: 0.3382
[Epoch 6] Train Loss: 1.5765, Acc: 0.4282 | Test Loss: 1.5715, Acc: 0.4320
[Epoch 7] Train Loss: 1.5143, Acc: 0.4430 | Test Loss: 1.5326, Acc: 0.4519
[Epoch 8] Train Loss: 1.4777, Acc: 0.4606 | Test Loss: 1.5251, Acc: 0.4494
[Epoch 9] Train Loss: 1.4265, Acc: 0.4762 | Test Loss: 1.7063, Acc: 0.3809
[Epoch 10] Train Loss: 1.3909, Acc: 0.4902 | Test Loss: 1.3316, Acc: 0.5187
[Epoch 11] Train Loss: 1.3721, Acc: 0.5026 | Test Loss: 1.8490, Acc: 0.3376
[Epoch 12] Train Loss: 1.3607, Acc: 0.5072 | Test Loss: 1.4968, Acc: 0.4493
[Epoch 13] Train Loss: 1.3593, Acc: 0.4940 | Test Loss: 1.2433, Acc: 0.5574
[Epoch 14] Train Loss: 1.3177, Acc: 0.5214 | Test Loss: 2.1883, Acc: 0.2971
[Epoch 15] Train Loss: 1.2932, Acc: 0.5258 | Test Loss: 1.5204, Acc: 0.4572
[Epoch 16] Train Loss: 1.2883, Acc: 0.5342 | Test Loss: 1.3748, Acc: 0.5173
[Epoch 17] Train Loss: 1.2670, Acc: 0.5348 | Test Loss: 1.3386, Acc: 0.5178
[Epoch 18] Train Loss: 1.2797, Acc: 0.5410 | Test Loss: 1.3324, Acc: 0.5100
[Epoch 19] Train Loss: 1.2533, Acc: 0.5464 | Test Loss: 1.3022, Acc: 0.5210
[Epoch 20] Train Loss: 1.2047, Acc: 0.5704 | Test Loss: 1.2864, Acc: 0.5383
[Epoch 21] Train Loss: 1.2022, Acc: 0.5598 | Test Loss: 1.4837, Acc: 0.4757
[Epoch 22] Train Loss: 1.1995, Acc: 0.5632 | Test Loss: 1.3956, Acc: 0.4926
[Epoch 23] Train Loss: 1.1765, Acc: 0.5698 | Test Loss: 1.2908, Acc: 0.5334
[Epoch 24] Train Loss: 1.1608, Acc: 0.5816 | Test Loss: 1.3721, Acc: 0.5310
[Epoch 25] Train Loss: 1.1508, Acc: 0.5816 | Test Loss: 1.4807, Acc: 0.4607
[Epoch 26] Train Loss: 1.1099, Acc: 0.5964 | Test Loss: 1.1432, Acc: 0.5937
[Epoch 27] Train Loss: 1.1331, Acc: 0.5792 | Test Loss: 1.4181, Acc: 0.5094
[Epoch 28] Train Loss: 1.1020, Acc: 0.5994 | Test Loss: 1.2494, Acc: 0.5645
[Epoch 29] Train Loss: 1.0997, Acc: 0.6068 | Test Loss: 1.3318, Acc: 0.5333
[Epoch 30] Train Loss: 1.1039, Acc: 0.5950 | Test Loss: 1.2957, Acc: 0.5420
```

---
### 데이터 증강 실험 - C와 비교

1. 약한 증강 (RandomHorizontalFlip만 사용)
```
Configuration: Dropout=False, Aug=True, Weight Decay=0.0
[Epoch 1] Train Loss: 1.8651, Acc: 0.3140 | Test Loss: 1.7321, Acc: 0.3707
[Epoch 2] Train Loss: 1.6008, Acc: 0.4136 | Test Loss: 1.7344, Acc: 0.3867
[Epoch 3] Train Loss: 1.4726, Acc: 0.4684 | Test Loss: 1.5885, Acc: 0.4108
[Epoch 4] Train Loss: 1.3900, Acc: 0.5088 | Test Loss: 1.5717, Acc: 0.4439
[Epoch 5] Train Loss: 1.3197, Acc: 0.5356 | Test Loss: 1.5043, Acc: 0.4407
[Epoch 6] Train Loss: 1.2471, Acc: 0.5596 | Test Loss: 1.5402, Acc: 0.4533
[Epoch 7] Train Loss: 1.1896, Acc: 0.5870 | Test Loss: 1.3291, Acc: 0.5299
[Epoch 8] Train Loss: 1.1299, Acc: 0.6092 | Test Loss: 1.5717, Acc: 0.4728
[Epoch 9] Train Loss: 1.0706, Acc: 0.6254 | Test Loss: 1.3238, Acc: 0.5224
[Epoch 10] Train Loss: 1.0466, Acc: 0.6402 | Test Loss: 1.6342, Acc: 0.4622
[Epoch 11] Train Loss: 0.9988, Acc: 0.6490 | Test Loss: 1.3989, Acc: 0.5067
[Epoch 12] Train Loss: 0.9760, Acc: 0.6612 | Test Loss: 1.2225, Acc: 0.5702
[Epoch 13] Train Loss: 0.9519, Acc: 0.6638 | Test Loss: 1.1048, Acc: 0.6061
[Epoch 14] Train Loss: 0.9083, Acc: 0.6832 | Test Loss: 1.2629, Acc: 0.5573
[Epoch 15] Train Loss: 0.8828, Acc: 0.6942 | Test Loss: 1.0896, Acc: 0.6171
[Epoch 16] Train Loss: 0.8680, Acc: 0.6984 | Test Loss: 1.0942, Acc: 0.6163
[Epoch 17] Train Loss: 0.8423, Acc: 0.7120 | Test Loss: 1.3516, Acc: 0.5452
[Epoch 18] Train Loss: 0.8166, Acc: 0.7182 | Test Loss: 1.2114, Acc: 0.5755
[Epoch 19] Train Loss: 0.8212, Acc: 0.7086 | Test Loss: 1.1508, Acc: 0.5960
[Epoch 20] Train Loss: 0.7830, Acc: 0.7268 | Test Loss: 1.5702, Acc: 0.4974
[Epoch 21] Train Loss: 0.7573, Acc: 0.7342 | Test Loss: 1.1306, Acc: 0.6090
[Epoch 22] Train Loss: 0.7343, Acc: 0.7488 | Test Loss: 1.5027, Acc: 0.5523
[Epoch 23] Train Loss: 0.7541, Acc: 0.7340 | Test Loss: 1.4216, Acc: 0.5417
[Epoch 24] Train Loss: 0.7007, Acc: 0.7608 | Test Loss: 1.0294, Acc: 0.6375
[Epoch 25] Train Loss: 0.6718, Acc: 0.7710 | Test Loss: 1.0182, Acc: 0.6484
[Epoch 26] Train Loss: 0.6624, Acc: 0.7720 | Test Loss: 1.0597, Acc: 0.6377
[Epoch 27] Train Loss: 0.6481, Acc: 0.7722 | Test Loss: 1.0885, Acc: 0.6307
[Epoch 28] Train Loss: 0.6492, Acc: 0.7742 | Test Loss: 1.0679, Acc: 0.6378
[Epoch 29] Train Loss: 0.6182, Acc: 0.7876 | Test Loss: 1.3893, Acc: 0.5660
[Epoch 30] Train Loss: 0.6082, Acc: 0.7916 | Test Loss: 1.2425, Acc: 0.5987
```

2. 강한 증강 ((RandomHorizontalFlip, Random crop, ColorJitter 사용))
```
Configuration: Dropout=False, Aug=True, Weight Decay=0.0
[Epoch 1] Train Loss: 1.9731, Acc: 0.2624 | Test Loss: 1.7924, Acc: 0.3407
[Epoch 2] Train Loss: 1.7649, Acc: 0.3474 | Test Loss: 1.8809, Acc: 0.2983
[Epoch 3] Train Loss: 1.6602, Acc: 0.3844 | Test Loss: 1.9563, Acc: 0.3537
[Epoch 4] Train Loss: 1.6039, Acc: 0.4046 | Test Loss: 1.6466, Acc: 0.4031
[Epoch 5] Train Loss: 1.5489, Acc: 0.4262 | Test Loss: 1.8983, Acc: 0.3662
[Epoch 6] Train Loss: 1.4984, Acc: 0.4620 | Test Loss: 1.4683, Acc: 0.4709
[Epoch 7] Train Loss: 1.4428, Acc: 0.4732 | Test Loss: 2.2753, Acc: 0.3336
[Epoch 8] Train Loss: 1.4418, Acc: 0.4772 | Test Loss: 1.6683, Acc: 0.4427
[Epoch 9] Train Loss: 1.3788, Acc: 0.4964 | Test Loss: 1.5233, Acc: 0.4508
[Epoch 10] Train Loss: 1.3625, Acc: 0.5132 | Test Loss: 2.0705, Acc: 0.3653
[Epoch 11] Train Loss: 1.3187, Acc: 0.5220 | Test Loss: 1.5137, Acc: 0.4636
[Epoch 12] Train Loss: 1.2857, Acc: 0.5430 | Test Loss: 1.3720, Acc: 0.5128
[Epoch 13] Train Loss: 1.2426, Acc: 0.5530 | Test Loss: 1.2557, Acc: 0.5498
[Epoch 14] Train Loss: 1.2125, Acc: 0.5636 | Test Loss: 1.2398, Acc: 0.5516
[Epoch 15] Train Loss: 1.2269, Acc: 0.5550 | Test Loss: 1.5559, Acc: 0.4775
[Epoch 16] Train Loss: 1.1921, Acc: 0.5802 | Test Loss: 1.1655, Acc: 0.5861
[Epoch 17] Train Loss: 1.1706, Acc: 0.5834 | Test Loss: 1.1409, Acc: 0.5930
[Epoch 18] Train Loss: 1.1482, Acc: 0.5950 | Test Loss: 1.2498, Acc: 0.5663
[Epoch 19] Train Loss: 1.1103, Acc: 0.5990 | Test Loss: 1.4172, Acc: 0.5173
[Epoch 20] Train Loss: 1.0946, Acc: 0.6136 | Test Loss: 1.3495, Acc: 0.5287
[Epoch 21] Train Loss: 1.0920, Acc: 0.6230 | Test Loss: 1.3733, Acc: 0.5199
[Epoch 22] Train Loss: 1.0722, Acc: 0.6222 | Test Loss: 1.2762, Acc: 0.5640
[Epoch 23] Train Loss: 1.0730, Acc: 0.6262 | Test Loss: 2.1496, Acc: 0.4096
[Epoch 24] Train Loss: 1.0463, Acc: 0.6414 | Test Loss: 1.3459, Acc: 0.5531
[Epoch 25] Train Loss: 1.0217, Acc: 0.6436 | Test Loss: 1.1107, Acc: 0.6084
[Epoch 26] Train Loss: 1.0025, Acc: 0.6438 | Test Loss: 1.4673, Acc: 0.5367
[Epoch 27] Train Loss: 1.0142, Acc: 0.6372 | Test Loss: 1.3690, Acc: 0.5489
[Epoch 28] Train Loss: 0.9951, Acc: 0.6450 | Test Loss: 1.3052, Acc: 0.5654
[Epoch 29] Train Loss: 0.9788, Acc: 0.6596 | Test Loss: 1.3442, Acc: 0.5581
[Epoch 30] Train Loss: 0.9819, Acc: 0.6612 | Test Loss: 1.1717, Acc: 0.5999
```

## 가중치 감소 실험 - 1e-3, 1e-4, 1e-5 비교 (A)

1. 1e-3
```
Configuration: Dropout=False, Aug=False, Weight Decay=0.001
[Epoch 1] Train Loss: 1.8622, Acc: 0.3274 | Test Loss: 1.8379, Acc: 0.3435
[Epoch 2] Train Loss: 1.5874, Acc: 0.4242 | Test Loss: 1.5910, Acc: 0.4342
[Epoch 3] Train Loss: 1.4714, Acc: 0.4706 | Test Loss: 1.7895, Acc: 0.3790
[Epoch 4] Train Loss: 1.3702, Acc: 0.5066 | Test Loss: 1.4887, Acc: 0.4558
[Epoch 5] Train Loss: 1.2813, Acc: 0.5428 | Test Loss: 1.4666, Acc: 0.4426
[Epoch 6] Train Loss: 1.2157, Acc: 0.5662 | Test Loss: 1.3462, Acc: 0.5120
[Epoch 7] Train Loss: 1.1611, Acc: 0.5888 | Test Loss: 1.3542, Acc: 0.5054
[Epoch 8] Train Loss: 1.1087, Acc: 0.6136 | Test Loss: 1.3634, Acc: 0.5114
[Epoch 9] Train Loss: 1.0631, Acc: 0.6352 | Test Loss: 1.3294, Acc: 0.5335
[Epoch 10] Train Loss: 1.0407, Acc: 0.6364 | Test Loss: 1.1850, Acc: 0.5713
[Epoch 11] Train Loss: 0.9691, Acc: 0.6642 | Test Loss: 1.1961, Acc: 0.5618
[Epoch 12] Train Loss: 0.9288, Acc: 0.6780 | Test Loss: 1.2410, Acc: 0.5532
[Epoch 13] Train Loss: 0.8886, Acc: 0.6960 | Test Loss: 1.6168, Acc: 0.4522
[Epoch 14] Train Loss: 0.8821, Acc: 0.6964 | Test Loss: 2.0989, Acc: 0.3917
[Epoch 15] Train Loss: 0.8445, Acc: 0.7092 | Test Loss: 1.3615, Acc: 0.5174
[Epoch 16] Train Loss: 0.8134, Acc: 0.7274 | Test Loss: 1.0993, Acc: 0.6049
[Epoch 17] Train Loss: 0.7701, Acc: 0.7450 | Test Loss: 1.2322, Acc: 0.5602
[Epoch 18] Train Loss: 0.7658, Acc: 0.7406 | Test Loss: 1.2536, Acc: 0.5565
[Epoch 19] Train Loss: 0.7406, Acc: 0.7564 | Test Loss: 1.2533, Acc: 0.5720
[Epoch 20] Train Loss: 0.7117, Acc: 0.7598 | Test Loss: 1.0876, Acc: 0.6231
[Epoch 21] Train Loss: 0.6790, Acc: 0.7784 | Test Loss: 1.1234, Acc: 0.5967
[Epoch 22] Train Loss: 0.6575, Acc: 0.7862 | Test Loss: 1.4577, Acc: 0.5270
[Epoch 23] Train Loss: 0.6262, Acc: 0.7894 | Test Loss: 1.0731, Acc: 0.6223
[Epoch 24] Train Loss: 0.6025, Acc: 0.8014 | Test Loss: 1.0648, Acc: 0.6341
[Epoch 25] Train Loss: 0.5725, Acc: 0.8146 | Test Loss: 1.2072, Acc: 0.6031
[Epoch 26] Train Loss: 0.5479, Acc: 0.8242 | Test Loss: 1.2894, Acc: 0.5803
[Epoch 27] Train Loss: 0.5295, Acc: 0.8328 | Test Loss: 1.2241, Acc: 0.5983
[Epoch 28] Train Loss: 0.5301, Acc: 0.8284 | Test Loss: 1.2979, Acc: 0.5715
[Epoch 29] Train Loss: 0.4995, Acc: 0.8408 | Test Loss: 1.2004, Acc: 0.6031
[Epoch 30] Train Loss: 0.4709, Acc: 0.8580 | Test Loss: 1.1520, Acc: 0.6321
```

2. 1e-4
```
Configuration: Dropout=False, Aug=False, Weight Decay=0.0001
[Epoch 1] Train Loss: 1.8208, Acc: 0.3338 | Test Loss: 1.7486, Acc: 0.3554
[Epoch 2] Train Loss: 1.5533, Acc: 0.4402 | Test Loss: 1.5724, Acc: 0.4339
[Epoch 3] Train Loss: 1.4258, Acc: 0.4756 | Test Loss: 1.5119, Acc: 0.4581
[Epoch 4] Train Loss: 1.3408, Acc: 0.5160 | Test Loss: 1.5031, Acc: 0.4550
[Epoch 5] Train Loss: 1.2533, Acc: 0.5550 | Test Loss: 1.4972, Acc: 0.4632
[Epoch 6] Train Loss: 1.1843, Acc: 0.5758 | Test Loss: 1.7891, Acc: 0.4031
[Epoch 7] Train Loss: 1.1380, Acc: 0.5964 | Test Loss: 1.4201, Acc: 0.4870
[Epoch 8] Train Loss: 1.0752, Acc: 0.6220 | Test Loss: 1.4019, Acc: 0.4899
[Epoch 9] Train Loss: 1.0303, Acc: 0.6292 | Test Loss: 1.2436, Acc: 0.5490
[Epoch 10] Train Loss: 0.9969, Acc: 0.6486 | Test Loss: 1.1911, Acc: 0.5697
[Epoch 11] Train Loss: 0.9543, Acc: 0.6676 | Test Loss: 1.1627, Acc: 0.5792
[Epoch 12] Train Loss: 0.9221, Acc: 0.6806 | Test Loss: 1.5526, Acc: 0.4818
[Epoch 13] Train Loss: 0.8866, Acc: 0.6960 | Test Loss: 1.6729, Acc: 0.4742
[Epoch 14] Train Loss: 0.8454, Acc: 0.7110 | Test Loss: 1.3375, Acc: 0.5343
[Epoch 15] Train Loss: 0.8211, Acc: 0.7200 | Test Loss: 1.1739, Acc: 0.5857
[Epoch 16] Train Loss: 0.7850, Acc: 0.7320 | Test Loss: 1.3316, Acc: 0.5470
[Epoch 17] Train Loss: 0.7591, Acc: 0.7436 | Test Loss: 1.2453, Acc: 0.5686
[Epoch 18] Train Loss: 0.7301, Acc: 0.7572 | Test Loss: 1.7020, Acc: 0.4898
[Epoch 19] Train Loss: 0.7037, Acc: 0.7656 | Test Loss: 1.3248, Acc: 0.5615
[Epoch 20] Train Loss: 0.6640, Acc: 0.7842 | Test Loss: 1.0785, Acc: 0.6268
[Epoch 21] Train Loss: 0.6279, Acc: 0.7898 | Test Loss: 1.4167, Acc: 0.5365
[Epoch 22] Train Loss: 0.6088, Acc: 0.7982 | Test Loss: 1.0885, Acc: 0.6179
[Epoch 23] Train Loss: 0.5862, Acc: 0.8070 | Test Loss: 1.3346, Acc: 0.5570
[Epoch 24] Train Loss: 0.5531, Acc: 0.8184 | Test Loss: 1.5488, Acc: 0.5278
[Epoch 25] Train Loss: 0.5378, Acc: 0.8312 | Test Loss: 1.1311, Acc: 0.6262
[Epoch 26] Train Loss: 0.5512, Acc: 0.8184 | Test Loss: 1.3423, Acc: 0.5713
[Epoch 27] Train Loss: 0.4969, Acc: 0.8398 | Test Loss: 1.1706, Acc: 0.6100
[Epoch 28] Train Loss: 0.4739, Acc: 0.8506 | Test Loss: 1.4750, Acc: 0.5373
[Epoch 29] Train Loss: 0.4548, Acc: 0.8540 | Test Loss: 1.4245, Acc: 0.5512
[Epoch 30] Train Loss: 0.4304, Acc: 0.8584 | Test Loss: 1.2449, Acc: 0.6038
```

3. 1e-5
```
Configuration: Dropout=False, Aug=False, Weight Decay=1e-05
[Epoch 1] Train Loss: 1.8342, Acc: 0.3246 | Test Loss: 1.7287, Acc: 0.3779
[Epoch 2] Train Loss: 1.5711, Acc: 0.4334 | Test Loss: 1.7924, Acc: 0.3298
[Epoch 3] Train Loss: 1.4613, Acc: 0.4670 | Test Loss: 1.5124, Acc: 0.4421
[Epoch 4] Train Loss: 1.3972, Acc: 0.4968 | Test Loss: 1.4761, Acc: 0.4763
[Epoch 5] Train Loss: 1.2907, Acc: 0.5416 | Test Loss: 1.6655, Acc: 0.4319
[Epoch 6] Train Loss: 1.2371, Acc: 0.5632 | Test Loss: 1.4771, Acc: 0.4753
[Epoch 7] Train Loss: 1.1971, Acc: 0.5662 | Test Loss: 1.3826, Acc: 0.5012
[Epoch 8] Train Loss: 1.1081, Acc: 0.6106 | Test Loss: 1.3183, Acc: 0.5212
[Epoch 9] Train Loss: 1.0703, Acc: 0.6320 | Test Loss: 1.3330, Acc: 0.5232
[Epoch 10] Train Loss: 1.0041, Acc: 0.6596 | Test Loss: 1.3501, Acc: 0.5224
[Epoch 11] Train Loss: 0.9766, Acc: 0.6660 | Test Loss: 1.1629, Acc: 0.5839
[Epoch 12] Train Loss: 0.9214, Acc: 0.6876 | Test Loss: 1.1302, Acc: 0.5964
[Epoch 13] Train Loss: 0.9034, Acc: 0.6828 | Test Loss: 1.1540, Acc: 0.5863
[Epoch 14] Train Loss: 0.8495, Acc: 0.7134 | Test Loss: 1.5408, Acc: 0.4985
[Epoch 15] Train Loss: 0.8229, Acc: 0.7190 | Test Loss: 1.2165, Acc: 0.5709
[Epoch 16] Train Loss: 0.7893, Acc: 0.7304 | Test Loss: 1.1371, Acc: 0.6031
[Epoch 17] Train Loss: 0.7634, Acc: 0.7418 | Test Loss: 1.2317, Acc: 0.5819
[Epoch 18] Train Loss: 0.7243, Acc: 0.7504 | Test Loss: 1.2742, Acc: 0.5757
[Epoch 19] Train Loss: 0.6957, Acc: 0.7684 | Test Loss: 1.1658, Acc: 0.5915
[Epoch 20] Train Loss: 0.6789, Acc: 0.7716 | Test Loss: 1.3274, Acc: 0.5562
[Epoch 21] Train Loss: 0.6484, Acc: 0.7864 | Test Loss: 1.1053, Acc: 0.6237
[Epoch 22] Train Loss: 0.6207, Acc: 0.7912 | Test Loss: 1.4909, Acc: 0.5163
[Epoch 23] Train Loss: 0.5989, Acc: 0.8028 | Test Loss: 1.1275, Acc: 0.6080
[Epoch 24] Train Loss: 0.5796, Acc: 0.8122 | Test Loss: 1.0941, Acc: 0.6243
[Epoch 25] Train Loss: 0.5485, Acc: 0.8128 | Test Loss: 1.2964, Acc: 0.5799
[Epoch 26] Train Loss: 0.5334, Acc: 0.8200 | Test Loss: 1.4465, Acc: 0.5490
[Epoch 27] Train Loss: 0.5012, Acc: 0.8382 | Test Loss: 1.2264, Acc: 0.6029
[Epoch 28] Train Loss: 0.4765, Acc: 0.8476 | Test Loss: 1.2287, Acc: 0.5967
[Epoch 29] Train Loss: 0.4520, Acc: 0.8540 | Test Loss: 1.5605, Acc: 0.5114
[Epoch 30] Train Loss: 0.4292, Acc: 0.8660 | Test Loss: 1.2887, Acc: 0.5910
```