# Mediapipe 기반 한글 수어 번역기

본 프로젝트는 Mediapipe를 이용하여 실시간으로 손 모양을 인식하고 한글 수어를 번역하는 프로그램입니다.

## 주요 기능

- 손가락 관절 위치를 기반으로 특징 벡터 추출
- Random Forest 분류기를 사용한 수어 학습 및 예측
- 슬라이딩 윈도우 기반의 실시간 수어 인식 알고리즘
- GUI 사용자 인터페이스

## 구성 파일

- `notebooks/`: 데이터 수집, 학습, 실행용 Jupyter 노트북
- `models/`: 학습된 모델 파일 (.p)
- `data/`: 캡처된 데이터 파일 (.pickle)
- `docs/`: 캡스톤 디자인 논문

## 실행 방법

1. 필요한 패키지 설치

```bash
pip install -r requirements.txt

2. notebooks/inference_classifier.ipynb 파일을 실행하여 사용자 인터페이스 사용

논문
해당 프로젝트는 2024년 한밭대학교 캡스톤 디자인 프로젝트로 수행되었습니다.
자세한 내용은 docs/Sign Language Translation Program with Mediapipe.pdf를 참고하세요.
```
