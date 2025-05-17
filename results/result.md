## Discussion



---

## Experiment A: Basic model (Observe overfitting)
- run_experiment(dropout=False, use_aug=False, weight_decay=0.0)
- 정규화 기법을 사용하지 않은 기본 모델
- Train Loss: 0.3127, Acc: 0.9128 | Test Loss: 1.6552, Acc: 0.5213

![Image](https://github.com/user-attachments/assets/10f7571a-a648-485b-98f0-d4f6a3220bc2)

## Experiment B: Dropout only
- run_experiment(dropout=True, use_aug=False, weight_decay=0.0)
- Dropout만 사용한 모델
- Train Loss: 0.8413, Acc: 0.6992 | Test Loss: 1.8075, Acc: 0.4261

![Image](https://github.com/user-attachments/assets/7563d2f8-bb65-476c-89b3-acc3aee4ffa0)

## Experiment C: Data Augmentation only
- run_experiment(dropout=False, use_aug=True, weight_decay=0.0)
- Data Augmentation만 사용한 모델
- Train Loss: 0.9378, Acc: 0.6708 | Test Loss: 1.5137, Acc: 0.5180


![Image](https://github.com/user-attachments/assets/b5e2720a-4d61-4c32-a699-f88968d73bcd)


## Experiment D: Dropout + Augmentation + Weight Decay
- run_experiment(dropout=True, use_aug=True, weight_decay=1e-4)
- 세가지 정규화 기법을 모두 적용한 모델
- Train Loss: 1.2336, Acc: 0.5436 | Test Loss: 1.3148, Acc: 0.5227


![Image](https://github.com/user-attachments/assets/d92e9e04-ba27-4fa5-be36-e4b9148997c4)

## Experiment E: Weight Decay only
- run_experiment(dropout=False, use_aug=False, weight_decay=1e-4)
- Weight decay만 적용한 모델
- Train Loss: 0.2769, Acc: 0.9286 | Test Loss: 2.4990, Acc: 0.4451

