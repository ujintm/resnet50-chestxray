# Chest X-ray Multi-label Classification

NIH ChestX-ray14 데이터셋을 활용하여 멀티라벨 질병 분류 모델을 구축하고,  
성능 개선 실험을 반복하며 모델 구조 및 학습 전략을 비교

## ✅ 실험 구성

- **Baseline**: ResNet50 (pretrained, backbone freeze)
- **Finetune**: ResNet50 unfreeze + augmentation 추가
- **Model Comparison**: DenseNet121 모델로 구조 변경

## 🎯 평가 지표

- Accuracy
- F1 score (macro)
- AUC (ROC)
- Sensitivity / Specificity

## 📦 결과 저장

- `checkpoints/`: epoch별 모델 저장
- `metrics.csv`: 각 epoch별 지표 로그
- `*.png`: 지표별 시각화 그래프
