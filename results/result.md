## Discussion

- Dropout이 단일 기법으로는 가장 효과적이었음
- 데이터 증강은 단독으로 사용될 경우 효과가 제한적
- 실험 B가 가장 안정적인 모델임을 관찰함
- 과적합 감소 vs 성능 trade-off

---

## Experiment A: Basic model (Observe overfitting)
- run_experiment(dropout=False, use_aug=False, weight_decay=0.0)
- 정규화 기법을 사용하지 않은 기본 모델
- Train Acc: 77.16%, Test Acc: 58.09%
- Train Loss: 0.6719, Test Loss: 1.2383
- 강한 과적합 관찰됨

![Image](https://github.com/user-attachments/assets/10f7571a-a648-485b-98f0-d4f6a3220bc2)
((0.6719401271282872, 1.2383258490805413), (0.7716, 0.5809))

## Experiment B: Dropout only
- run_experiment(dropout=True, use_aug=False, weight_decay=0.0)
- Dropout만 사용한 모델
- Train Acc: 59.42%, Test Acc: 56.47%
- Train Loss: 1.1168, Test Loss: 1.2057
- 과적합은 감소했으나, 전체적인 성능이 A보다 낮아짐

![Image](https://github.com/user-attachments/assets/7563d2f8-bb65-476c-89b3-acc3aee4ffa0)
((1.1168080304242387, 1.205691329233206), (0.5942, 0.5647))

## Experiment C: Data Augmentation only
- run_experiment(dropout=False, use_aug=True, weight_decay=0.0)
- Data Augmentation만 사용한 모델
- Train Acc: 66.68%, Test Acc: 47.68%
- Train Loss: 0.9377, Test Loss: 1.7948
- 과적합이 관찰되었고, 테스트 손실도 다른 모델에 비해 가장 큼.

![Image](https://github.com/user-attachments/assets/b5e2720a-4d61-4c32-a699-f88968d73bcd)


## Experiment D: Dropout + Augmentation + Weight Decay
- run_experiment(dropout=True, use_aug=True, weight_decay=1e-4)
- 세가지 정규화 기법을 모두 적용한 모델
- Train Acc: 56.00%, Test Acc: 50.21%
- Train Loss: 1.2271, Test Loss: 1.3961
- 과적합이 감소함. 그러나 테스트 정확도는 B보다 낮아짐. 


![Image](https://github.com/user-attachments/assets/d92e9e04-ba27-4fa5-be36-e4b9148997c4)
((1.2271296019795574, 1.3961455168997405), (0.56, 0.5021))