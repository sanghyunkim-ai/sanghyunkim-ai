# 김상현 | Medical Imaging & Healthcare AI

생명과학과 의생명과학 연구 경험을 기반으로 의료영상 AI와 헬스케어 데이터 분석을 공부하고 있습니다.

피부 세포 노화 및 난임 연구 경험을 보유하고 있으며, 현재는 CT·MRI·흉부 X-ray 데이터를 활용한 의료영상 전처리, 분류, 객체탐지, 분할 모델 개발에 집중하고 있습니다.

📍 Seoul, South Korea  
📧 tjdfud5759@naver.com

---

## 관심 분야

- Medical Imaging AI
- Healthcare Data Analysis
- Deep Learning
- Explainable AI
- Clinical Data Machine Learning

---

## 기술 스택

### Programming & Data Analysis

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- scikit-learn

### Deep Learning & Medical Imaging

- PyTorch
- torchvision
- ResNet
- U-Net
- YOLOv8
- OpenCV
- pydicom
- Grad-CAM

### Machine Learning

- LightGBM
- XGBoost
- CatBoost
- SHAP
- Optuna
- Cross Validation
- Ensemble

### Database

- SQL
- MySQL
- SQLAlchemy Core
- MongoDB
- PyMongo

### Development Environment

- Google Colab
- Kaggle Notebook
- Git
- GitHub
- VS Code

---

## 대표 포트폴리오

### 1. Medical Imaging AI Portfolio

CT DICOM 전처리부터 흉부 X-ray 분류·객체탐지, 뇌 MRI 종양 분할까지 의료영상 AI 프로젝트 4개를 종합한 포트폴리오입니다.

[프로젝트 저장소](https://github.com/tjdfud5759-crypto/medical-imaging-ai-portfolio)

주요 내용:

- CT DICOM HU 변환 및 Windowing
- ResNet18 기반 흉부 X-ray 결핵 분류
- YOLOv8 기반 14종 흉부 X-ray 이상 소견 탐지
- U-Net 기반 뇌 MRI 종양 분할

---

### 2. Chest X-ray Tuberculosis Classification

Basic CNN과 ResNet18 전이학습 모델을 비교하여 정상과 결핵 흉부 X-ray를 분류했습니다.

[프로젝트 저장소](https://github.com/tjdfud5759-crypto/chest-xray-tb-classification)

주요 결과:

- Test Accuracy: `0.9968`
- Test Recall: `0.9810`
- Test AUROC: `0.998839`
- Grad-CAM 기반 예측 영역 시각화

기술:

`PyTorch` `ResNet18` `Transfer Learning` `AMP` `Grad-CAM`

---

### 3. Chest X-ray Abnormality Detection

VinBigData 흉부 X-ray 데이터에서 YOLOv8s를 이용하여 14종 이상 소견의 종류와 위치를 탐지했습니다.

[프로젝트 저장소](https://github.com/tjdfud5759-crypto/vinbigdata-chest-xray-abnormality-detection)

주요 결과:

- 원본 Bounding Box: `36,096개`
- Consensus Bounding Box: `23,940개`
- 최종 mAP50: `0.2992`
- 최종 mAP50-95: `0.1481`


기술:

`YOLOv8` `PyTorch` `OpenCV` `Object Detection` `IoU` `mAP`

---

### 4. Brain MRI Tumor Segmentation

환자 단위로 데이터를 분리하고, Baseline U-Net과 개선 U-Net의 종양 분할 성능을 비교했습니다.

[프로젝트 저장소](https://github.com/tjdfud5759-crypto/brain-mri-tumor-segmentation)

주요 결과:

- Positive Dice: `0.4814 → 0.6104`
- Patient-level Dice: `0.5198 → 0.6096`
- 종양 완전 누락률: `32.72% → 13.36%`
- Validation 기반 최종 Threshold: `0.925`

기술:

`PyTorch` `U-Net` `Dice Loss` `Oversampling` `Threshold Optimization`

---

### 5. Fertility Treatment Pregnancy Success Prediction

난임 시술 데이터를 이용하여 임신 성공 확률을 예측하고, SHAP을 통해 주요 예측 변수를 분석했습니다.

[프로젝트 저장소](https://github.com/tjdfud5759-crypto/fertility-treatment-pregnancy-success-prediction)

주요 내용:

- LightGBM·XGBoost·CatBoost 모델 비교
- 난임 도메인 기반 Feature Engineering
- Feature Importance 및 SHAP 분석
- 해석 가능한 최종 22개 Feature 선정
- Optuna 및 Stratified Cross Validation
- 임신 성공 확률 예측 파일 생성

기술:

`LightGBM` `XGBoost` `CatBoost` `SHAP` `Optuna` `Cross Validation`

---

## 기타 헬스케어 데이터 프로젝트

### Wearable Biometric Risk Monitoring

SQLAlchemy Core와 PyMongo를 활용하여 웨어러블 생체신호 데이터를 MySQL과 MongoDB에 저장하고 위험 이벤트를 분석했습니다.

[프로젝트 저장소](https://github.com/tjdfud5759-crypto/wearable-biometric-risk-monitoring)

### Healthcare SQL Analysis

환자·진단·방문 테이블을 설계하고 JOIN과 집계 함수를 이용하여 조건 기반 환자 데이터를 분석했습니다.

[프로젝트 저장소](https://github.com/tjdfud5759-crypto/healthcare-sql-high-risk-patient-analysis)

### Smoking Status Health Analysis

흡연자와 비흡연자의 건강 지표를 비교하고 시각화, 상관관계 분석 및 통계 검정을 수행했습니다.

[프로젝트 저장소](https://github.com/tjdfud5759-crypto/smoking-status-health-analysis)

---

## 학력

### 아주대학교

의생명과학과 석사  
아주대학교 피부과학교실  
2023.02 – 2025.02

### 목포대학교

생명과학과 학사  
2011.03 – 2019.08

---

## 연구 경력

### 난임연구소 연구원

서울라헬여성의원  
2025.03 – 2025.11

- 사람 유래 검체 취급
- 정자 검사
- 인공수정 관련 연구 및 실무

### 난임연구소 연구원

분당차병원  
2026.01

### Healthcare AI Bootcamp

2026.04 – Present

- 헬스케어 데이터 분석
- 머신러닝 및 딥러닝
- 의료영상 AI
- SQL 및 데이터베이스
- Git과 GitHub

---

## 연구 경험

### 피부 세포 및 노화 모델

- UVB 유도 Human Melanocyte 노화 모델 구축
- UVA 유도 Fibroblast 노화 모델 구축
- Melanocyte 및 Fibroblast 세포 배양
- Autophagy 및 Melanogenesis 관련 기능 분석
- Melanin Content 및 Tyrosinase Activity 평가

### 실험 기술

- qPCR
- Western Blotting
- Immunocytochemistry
- Flow Cytometry
- MTT Assay
- ELISA
- β-galactosidase Staining
- Confocal Microscopy

---

## 학술 및 연구 성과

### 석사 학위 논문

**Inhibitory Effects of CXCR4-specific SDF-1 Peptide (DGKPVSLSYR) on Melanogenesis in Human Melanocytes**

### 학술 발표

**Autophagy Dysfunction in Senescent Melanocytes: Impact of Melanin Accumulation and Subsequent ROS Generation**

제31회 대한피부과학연구학회 연례학술대회, 2024

### 특허 출원

**CXCR4 특이적 SDF-1 Peptide의 피부 미백 효능**

피부 색소 형성 억제용 조성물

---

## 자격 및 어학

- 정보처리기사 필기 합격
- 컴퓨터활용능력 2급
- OPIc IM1
- TOEIC Speaking IM2

---

## Contact

📧 tjdfud5759@naver.com
