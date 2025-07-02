# Vision Transformer (ViT) 테스트

AWS Inferentia/Trainium에서 Vision Transformer 모델을 테스트하기 위한 코드입니다.

## 파일 구성

- `1_vit_inf2.ipynb`: Inferentia2에서 ViT 모델 compile 후 테스트 (EC2 Inferentia 2 instance 테스트)
- `2_vit_sagemaker.ipynb`: SageMaker에서 ViT 모델 배포 (SageMaker Jupyter notebook 환경에서 테스트)
- `3_vit_sagemaker_inf.ipynb`: SageMaker 통한 Inferentia에서 ViT 모델 배포 (SageMaker Jupyter notebook 환경에서 테스트)

## 지원 하드웨어

- AWS Inferentia 2, Trainium 1

## 사용 방법

각 Jupyter 노트북을 순서대로 실행하면서 Inferentia, SageMaker를 활용한 ViT 관련 테스트를 진행할 수 있습니다.
