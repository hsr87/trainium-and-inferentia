# AWS Inferentia/Trainium Testing Repository

이 저장소는 AWS Inferentia와 Trainium 칩에서 다양한 AIML 모델을 테스트하기 위한 프로젝트입니다.

## 현재 상태

- **ViT (Vision Transformer)**: `vit/` 폴더에 ViT 모델 테스트 코드가 구현되어 있습니다.
- **향후 계획**: 추가적인 모델들에 대한 테스트 코드가 지속적으로 업데이트될 예정입니다.

## 폴더 구조

```
vit-inf2/
├── vit/                    # Vision Transformer 테스트 코드
└── README.md              # 프로젝트 설명서
```

## 지원 하드웨어

- AWS Inferentia (추론 최적화)
- AWS Trainium (훈련 최적화)

## 사용 방법

각 모델별 폴더에서 해당 모델의 README를 참조하여 테스트를 진행하세요.