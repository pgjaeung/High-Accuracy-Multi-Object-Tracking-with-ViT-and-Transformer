# High-Accuracy Multi-Object Tracking with ViT & Transformer

## 개요
이 프로젝트는 ViT 기반의 객체 탐지기, Transformer 기반의 시계열 예측, GTA를 활용한 글로벌 ID 연관 기법을 통해 정확도 중심의 Multi-Object Tracking 시스템을 구현합니다.

## 핵심 구성
- ViT-L 기반 객체 탐지기
- ROI 기반 ReID Embedding (shared backbone)
- Transformer 기반 motion prediction
- GTA: Long-term occlusion 대응
- Deep-EIoU: 정밀한 bbox regression

## 설치
```bash
conda env create -f environment.yml
conda activate mot-vit
