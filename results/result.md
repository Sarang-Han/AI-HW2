## Experiment A: Basic model (Observe overfitting)
- run_experiment(dropout=False, use_aug=False, weight_decay=0.0)

```
Configuration: Dropout=False, Aug=False, Weight Decay=0.0
[Epoch 1] Train Loss: 1.9655, Acc: 0.2660 | Test Loss: 1.8674, Acc: 0.3143
[Epoch 2] Train Loss: 1.7313, Acc: 0.3678 | Test Loss: 1.8045, Acc: 0.3458
[Epoch 3] Train Loss: 1.6375, Acc: 0.3960 | Test Loss: 1.9832, Acc: 0.2830
[Epoch 4] Train Loss: 1.5383, Acc: 0.4360 | Test Loss: 1.5928, Acc: 0.4100
[Epoch 5] Train Loss: 1.4457, Acc: 0.4832 | Test Loss: 1.9279, Acc: 0.3197
[Epoch 6] Train Loss: 1.3799, Acc: 0.5126 | Test Loss: 1.6516, Acc: 0.3971
[Epoch 7] Train Loss: 1.3070, Acc: 0.5274 | Test Loss: 1.4202, Acc: 0.4762
[Epoch 8] Train Loss: 1.2632, Acc: 0.5506 | Test Loss: 1.3034, Acc: 0.5377
[Epoch 9] Train Loss: 1.2252, Acc: 0.5684 | Test Loss: 1.3776, Acc: 0.4793
[Epoch 10] Train Loss: 1.1957, Acc: 0.5796 | Test Loss: 1.5322, Acc: 0.4633
[Epoch 11] Train Loss: 1.1532, Acc: 0.5826 | Test Loss: 1.3294, Acc: 0.5109
[Epoch 12] Train Loss: 1.1175, Acc: 0.6040 | Test Loss: 1.5591, Acc: 0.4587
[Epoch 13] Train Loss: 1.0740, Acc: 0.6202 | Test Loss: 1.4828, Acc: 0.4616
[Epoch 14] Train Loss: 1.0509, Acc: 0.6328 | Test Loss: 1.2427, Acc: 0.5509
[Epoch 15] Train Loss: 1.0184, Acc: 0.6408 | Test Loss: 1.8063, Acc: 0.4155
[Epoch 16] Train Loss: 0.9909, Acc: 0.6518 | Test Loss: 1.5429, Acc: 0.4849
[Epoch 17] Train Loss: 0.9676, Acc: 0.6596 | Test Loss: 2.1115, Acc: 0.4036
[Epoch 18] Train Loss: 0.9435, Acc: 0.6694 | Test Loss: 1.4140, Acc: 0.5160
[Epoch 19] Train Loss: 0.9081, Acc: 0.6858 | Test Loss: 1.4182, Acc: 0.4891
[Epoch 20] Train Loss: 0.9029, Acc: 0.6826 | Test Loss: 1.3308, Acc: 0.5363
[Epoch 21] Train Loss: 0.8500, Acc: 0.7016 | Test Loss: 1.4201, Acc: 0.5313
[Epoch 22] Train Loss: 0.8399, Acc: 0.7032 | Test Loss: 1.2920, Acc: 0.5603
[Epoch 23] Train Loss: 0.8410, Acc: 0.7060 | Test Loss: 1.3535, Acc: 0.5459
[Epoch 24] Train Loss: 0.7929, Acc: 0.7254 | Test Loss: 1.2964, Acc: 0.5460
[Epoch 25] Train Loss: 0.7512, Acc: 0.7422 | Test Loss: 1.2198, Acc: 0.5795
[Epoch 26] Train Loss: 0.7372, Acc: 0.7474 | Test Loss: 1.1094, Acc: 0.6016
[Epoch 27] Train Loss: 0.7227, Acc: 0.7528 | Test Loss: 1.3739, Acc: 0.5446
[Epoch 28] Train Loss: 0.6956, Acc: 0.7642 | Test Loss: 1.3236, Acc: 0.5425
[Epoch 29] Train Loss: 0.6978, Acc: 0.7598 | Test Loss: 1.2190, Acc: 0.5743
[Epoch 30] Train Loss: 0.6719, Acc: 0.7716 | Test Loss: 1.2383, Acc: 0.5809
```
![Image](https://github.com/user-attachments/assets/10f7571a-a648-485b-98f0-d4f6a3220bc2)
((0.6719401271282872, 1.2383258490805413), (0.7716, 0.5809))

## Experiment B: Dropout only
- run_experiment(dropout=True, use_aug=False, weight_decay=0.0)

```
Configuration: Dropout=True, Aug=False, Weight Decay=0.0
[Epoch 1] Train Loss: 2.0508, Acc: 0.2206 | Test Loss: 1.8841, Acc: 0.3110
[Epoch 2] Train Loss: 1.8431, Acc: 0.3074 | Test Loss: 1.7854, Acc: 0.3407
[Epoch 3] Train Loss: 1.7686, Acc: 0.3404 | Test Loss: 1.6360, Acc: 0.4123
[Epoch 4] Train Loss: 1.6782, Acc: 0.3704 | Test Loss: 1.7256, Acc: 0.3783
[Epoch 5] Train Loss: 1.6278, Acc: 0.3900 | Test Loss: 1.6186, Acc: 0.4143
[Epoch 6] Train Loss: 1.5691, Acc: 0.4230 | Test Loss: 1.6608, Acc: 0.3989
[Epoch 7] Train Loss: 1.5137, Acc: 0.4342 | Test Loss: 1.5854, Acc: 0.4234
[Epoch 8] Train Loss: 1.4945, Acc: 0.4420 | Test Loss: 1.4414, Acc: 0.4810
[Epoch 9] Train Loss: 1.4595, Acc: 0.4664 | Test Loss: 1.5954, Acc: 0.4201
[Epoch 10] Train Loss: 1.4466, Acc: 0.4668 | Test Loss: 1.7017, Acc: 0.3617
[Epoch 11] Train Loss: 1.4186, Acc: 0.4846 | Test Loss: 1.5235, Acc: 0.4518
[Epoch 12] Train Loss: 1.3692, Acc: 0.5062 | Test Loss: 1.4306, Acc: 0.4763
[Epoch 13] Train Loss: 1.3799, Acc: 0.5004 | Test Loss: 1.9860, Acc: 0.2985
[Epoch 14] Train Loss: 1.3277, Acc: 0.5122 | Test Loss: 1.5662, Acc: 0.4286
[Epoch 15] Train Loss: 1.3172, Acc: 0.5230 | Test Loss: 1.6107, Acc: 0.4026
[Epoch 16] Train Loss: 1.3116, Acc: 0.5266 | Test Loss: 1.5577, Acc: 0.4159
[Epoch 17] Train Loss: 1.3007, Acc: 0.5358 | Test Loss: 1.7591, Acc: 0.4055
[Epoch 18] Train Loss: 1.2788, Acc: 0.5468 | Test Loss: 1.2126, Acc: 0.5645
[Epoch 19] Train Loss: 1.2661, Acc: 0.5422 | Test Loss: 1.3006, Acc: 0.5297
[Epoch 20] Train Loss: 1.2461, Acc: 0.5512 | Test Loss: 1.2556, Acc: 0.5513
[Epoch 21] Train Loss: 1.2270, Acc: 0.5628 | Test Loss: 1.4602, Acc: 0.4671
[Epoch 22] Train Loss: 1.2096, Acc: 0.5570 | Test Loss: 1.4174, Acc: 0.4889
[Epoch 23] Train Loss: 1.1961, Acc: 0.5688 | Test Loss: 1.3952, Acc: 0.5125
[Epoch 24] Train Loss: 1.1831, Acc: 0.5778 | Test Loss: 1.3681, Acc: 0.5158
[Epoch 25] Train Loss: 1.1720, Acc: 0.5702 | Test Loss: 1.3156, Acc: 0.5039
[Epoch 26] Train Loss: 1.1594, Acc: 0.5770 | Test Loss: 1.3023, Acc: 0.5262
[Epoch 27] Train Loss: 1.1320, Acc: 0.5876 | Test Loss: 1.1982, Acc: 0.5739
[Epoch 28] Train Loss: 1.1262, Acc: 0.5928 | Test Loss: 1.5630, Acc: 0.4641
[Epoch 29] Train Loss: 1.1043, Acc: 0.6028 | Test Loss: 1.3669, Acc: 0.5312
[Epoch 30] Train Loss: 1.1168, Acc: 0.5942 | Test Loss: 1.2057, Acc: 0.5647
```
![Image](https://github.com/user-attachments/assets/7563d2f8-bb65-476c-89b3-acc3aee4ffa0)
((1.1168080304242387, 1.205691329233206), (0.5942, 0.5647))

## Experiment C: Data Augmentation only
- run_experiment(dropout=False, use_aug=True, weight_decay=0.0)

```
Configuration: Dropout=False, Aug=True, Weight Decay=0.0
[Epoch 1] Train Loss: 1.9503, Acc: 0.2672 | Test Loss: 2.0426, Acc: 0.2360
[Epoch 2] Train Loss: 1.7505, Acc: 0.3444 | Test Loss: 1.6836, Acc: 0.3507
[Epoch 3] Train Loss: 1.6275, Acc: 0.3926 | Test Loss: 1.6792, Acc: 0.3779
[Epoch 4] Train Loss: 1.5388, Acc: 0.4412 | Test Loss: 1.9092, Acc: 0.3096
[Epoch 5] Train Loss: 1.4836, Acc: 0.4518 | Test Loss: 1.5730, Acc: 0.4107
[Epoch 6] Train Loss: 1.4239, Acc: 0.4800 | Test Loss: 1.8328, Acc: 0.3749
[Epoch 7] Train Loss: 1.3757, Acc: 0.5028 | Test Loss: 1.6873, Acc: 0.4117
[Epoch 8] Train Loss: 1.3424, Acc: 0.5106 | Test Loss: 1.7117, Acc: 0.4212
[Epoch 9] Train Loss: 1.3041, Acc: 0.5396 | Test Loss: 1.7698, Acc: 0.3980
[Epoch 10] Train Loss: 1.2698, Acc: 0.5550 | Test Loss: 1.4879, Acc: 0.4688
[Epoch 11] Train Loss: 1.2321, Acc: 0.5640 | Test Loss: 1.5402, Acc: 0.4476
[Epoch 12] Train Loss: 1.2196, Acc: 0.5622 | Test Loss: 1.7661, Acc: 0.4034
[Epoch 13] Train Loss: 1.1892, Acc: 0.5788 | Test Loss: 1.4584, Acc: 0.4994
[Epoch 14] Train Loss: 1.1710, Acc: 0.5850 | Test Loss: 2.1120, Acc: 0.3690
[Epoch 15] Train Loss: 1.1388, Acc: 0.5978 | Test Loss: 1.2975, Acc: 0.5342
[Epoch 16] Train Loss: 1.1283, Acc: 0.6014 | Test Loss: 1.4457, Acc: 0.4928
[Epoch 17] Train Loss: 1.1150, Acc: 0.6086 | Test Loss: 1.5772, Acc: 0.4592
[Epoch 18] Train Loss: 1.0952, Acc: 0.6064 | Test Loss: 1.7658, Acc: 0.4341
[Epoch 19] Train Loss: 1.0636, Acc: 0.6224 | Test Loss: 1.3977, Acc: 0.5067
[Epoch 20] Train Loss: 1.0435, Acc: 0.6334 | Test Loss: 1.4669, Acc: 0.5091
[Epoch 21] Train Loss: 1.0297, Acc: 0.6282 | Test Loss: 2.0338, Acc: 0.4155
[Epoch 22] Train Loss: 1.0321, Acc: 0.6422 | Test Loss: 1.3247, Acc: 0.5393
[Epoch 23] Train Loss: 1.0214, Acc: 0.6274 | Test Loss: 1.3936, Acc: 0.5362
[Epoch 24] Train Loss: 1.0012, Acc: 0.6422 | Test Loss: 1.7032, Acc: 0.4886
[Epoch 25] Train Loss: 0.9986, Acc: 0.6480 | Test Loss: 2.3529, Acc: 0.3552
[Epoch 26] Train Loss: 0.9951, Acc: 0.6576 | Test Loss: 2.6797, Acc: 0.3271
[Epoch 27] Train Loss: 0.9735, Acc: 0.6598 | Test Loss: 1.4103, Acc: 0.5328
[Epoch 28] Train Loss: 0.9535, Acc: 0.6594 | Test Loss: 1.1986, Acc: 0.5906
[Epoch 29] Train Loss: 0.9398, Acc: 0.6620 | Test Loss: 1.5337, Acc: 0.4892
[Epoch 30] Train Loss: 0.9377, Acc: 0.6668 | Test Loss: 1.7948, Acc: 0.4768
```
![Image](https://github.com/user-attachments/assets/b5e2720a-4d61-4c32-a699-f88968d73bcd)


## Experiment D: Dropout + Augmentation + Weight Decay
- run_experiment(dropout=True, use_aug=True, weight_decay=1e-4)

```
Configuration: Dropout=True, Aug=True, Weight Decay=0.0001
[Epoch 1] Train Loss: 2.0620, Acc: 0.2190 | Test Loss: 1.9823, Acc: 0.2625
[Epoch 2] Train Loss: 1.8876, Acc: 0.2778 | Test Loss: 1.7788, Acc: 0.3164
[Epoch 3] Train Loss: 1.8085, Acc: 0.3134 | Test Loss: 1.8944, Acc: 0.3136
[Epoch 4] Train Loss: 1.7316, Acc: 0.3440 | Test Loss: 1.7082, Acc: 0.3732
[Epoch 5] Train Loss: 1.6830, Acc: 0.3636 | Test Loss: 1.8820, Acc: 0.2935
[Epoch 6] Train Loss: 1.6366, Acc: 0.3896 | Test Loss: 1.6725, Acc: 0.3647
[Epoch 7] Train Loss: 1.5868, Acc: 0.4112 | Test Loss: 1.7794, Acc: 0.3404
[Epoch 8] Train Loss: 1.5599, Acc: 0.4182 | Test Loss: 1.6617, Acc: 0.4061
[Epoch 9] Train Loss: 1.5468, Acc: 0.4164 | Test Loss: 1.7755, Acc: 0.3511
[Epoch 10] Train Loss: 1.4946, Acc: 0.4492 | Test Loss: 1.6863, Acc: 0.3952
[Epoch 11] Train Loss: 1.4713, Acc: 0.4528 | Test Loss: 1.5076, Acc: 0.4345
[Epoch 12] Train Loss: 1.4691, Acc: 0.4592 | Test Loss: 1.9635, Acc: 0.3157
[Epoch 13] Train Loss: 1.4533, Acc: 0.4566 | Test Loss: 1.4044, Acc: 0.4739
[Epoch 14] Train Loss: 1.4259, Acc: 0.4782 | Test Loss: 1.6553, Acc: 0.4324
[Epoch 15] Train Loss: 1.4145, Acc: 0.4928 | Test Loss: 1.4807, Acc: 0.4505
[Epoch 16] Train Loss: 1.4236, Acc: 0.4676 | Test Loss: 1.5298, Acc: 0.4349
[Epoch 17] Train Loss: 1.4056, Acc: 0.4926 | Test Loss: 1.8954, Acc: 0.3529
[Epoch 18] Train Loss: 1.3767, Acc: 0.4950 | Test Loss: 1.6418, Acc: 0.3923
[Epoch 19] Train Loss: 1.3566, Acc: 0.5110 | Test Loss: 1.3129, Acc: 0.5200
[Epoch 20] Train Loss: 1.3472, Acc: 0.5144 | Test Loss: 1.3166, Acc: 0.5267
[Epoch 21] Train Loss: 1.3317, Acc: 0.5106 | Test Loss: 1.3652, Acc: 0.4983
[Epoch 22] Train Loss: 1.3127, Acc: 0.5148 | Test Loss: 1.4469, Acc: 0.4837
[Epoch 23] Train Loss: 1.2937, Acc: 0.5356 | Test Loss: 1.5712, Acc: 0.4664
[Epoch 24] Train Loss: 1.2923, Acc: 0.5208 | Test Loss: 1.5305, Acc: 0.4521
[Epoch 25] Train Loss: 1.2751, Acc: 0.5404 | Test Loss: 1.2574, Acc: 0.5432
[Epoch 26] Train Loss: 1.2907, Acc: 0.5324 | Test Loss: 1.4651, Acc: 0.4687
[Epoch 27] Train Loss: 1.2474, Acc: 0.5468 | Test Loss: 1.3383, Acc: 0.5111
[Epoch 28] Train Loss: 1.2532, Acc: 0.5504 | Test Loss: 1.2812, Acc: 0.5459
[Epoch 29] Train Loss: 1.2630, Acc: 0.5470 | Test Loss: 1.2533, Acc: 0.5345
[Epoch 30] Train Loss: 1.2271, Acc: 0.5600 | Test Loss: 1.3961, Acc: 0.5021
```
![Image](https://github.com/user-attachments/assets/d92e9e04-ba27-4fa5-be36-e4b9148997c4)
((1.2271296019795574, 1.3961455168997405), (0.56, 0.5021))