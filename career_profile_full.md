# 김상현 | Medical Imaging & Healthcare AI

생명과학 석사 및 의생명과학 연구 경험을 바탕으로  
의료영상 AI와 헬스케어 데이터 분석 프로젝트를 수행하고 있습니다.

피부세포 노화·색소 형성 및 난임 연구 경험을 보유하고 있으며,  
CT·MRI·흉부 X-ray 데이터를 활용한 의료영상 전처리, 분류, 객체 탐지, 분할 모델을 구현했습니다.

생명과학 연구 경험과 Python 기반 인공지능 분석 역량을 연결하여  
임상 문제 해결에 기여하는 의료 AI 연구자를 목표로 하고 있습니다.

📍 Seoul, South Korea  
📧 tjdfud5759@naver.com  
🔗 [GitHub Portfolio](https://github.com/sanghyunkim-ai)

---

## 관심 분야

- Medical Imaging AI
- Healthcare Data Analysis
- Deep Learning
- Explainable AI
- Clinical Data Analysis

---

## 기술 스택

- **Programming & Data:** Python, pandas, NumPy, scikit-learn
- **Deep Learning:** PyTorch, torchvision, ResNet, U-Net, YOLOv8
- **Medical Imaging:** OpenCV, pydicom, Grad-CAM
- **Machine Learning:** LightGBM, XGBoost, CatBoost, SHAP, Optuna
- **Visualization & Statistics:** Matplotlib, Seaborn, SciPy
- **Database:** SQL, MySQL, MongoDB, SQLAlchemy Core, PyMongo
- **Development:** Git, GitHub, VS Code, Google Colab, Kaggle Notebook

---

## 대표 프로젝트

### 1. Medical Imaging AI Portfolio

CT DICOM 전처리부터 흉부 X-ray 분류·객체 탐지,  
뇌 MRI 종양 분할까지 의료영상 AI 프로젝트 4개를 종합한 포트폴리오입니다.

- CT DICOM HU 변환 및 Windowing
- ResNet18 기반 흉부 X-ray 결핵 분류
- YOLOv8 기반 14종 흉부 X-ray 이상 소견 탐지
- U-Net 기반 뇌 MRI 종양 분할

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/medical-imaging-ai-portfolio)

---

### 2. Chest X-ray Tuberculosis Classification

Basic CNN과 ResNet18 전이학습 모델을 비교하고,  
클래스 불균형을 반영하여 정상과 결핵 흉부 X-ray를 분류했습니다.

**주요 결과**

- Test Accuracy: `0.9968`
- Test Recall: `0.9810`
- Test AUROC: `0.998839`
- Grad-CAM 기반 예측 영역 시각화

**기술**

`PyTorch` `ResNet18` `Transfer Learning` `AMP` `Grad-CAM`

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/chest-xray-tb-classification)

---

### 3. Brain MRI Tumor Segmentation

환자 단위로 데이터를 분리하고,  
Baseline U-Net과 개선 U-Net의 뇌종양 분할 성능을 비교했습니다.

**주요 결과**

- Positive Dice: `0.4814 → 0.6104`
- Patient-level Dice: `0.5198 → 0.6096`
- 종양 완전 누락률: `32.72% → 13.36%`
- Validation 기반 최종 Threshold: `0.925`

**기술**

`PyTorch` `U-Net` `Dice Loss` `Oversampling` `Threshold Optimization`

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/brain-mri-tumor-segmentation)

---

### 4. Chest X-ray Abnormality Detection

VinBigData 흉부 X-ray 데이터에서 YOLOv8s를 활용하여  
14종 이상 소견의 종류와 위치를 탐지했습니다.

**주요 결과**

- 원본 Bounding Box: `36,096개`
- Consensus Bounding Box: `23,940개`
- 최종 mAP50: `0.2992`
- 최종 mAP50-95: `0.1481`
- 클래스별 성능 평가 및 정성적 오류 분석

**기술**

`YOLOv8` `PyTorch` `OpenCV` `Object Detection` `IoU` `mAP`

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/vinbigdata-chest-xray-abnormality-detection)

---

### 5. CT DICOM Preprocessing

CT DICOM 파일의 메타데이터와 픽셀 데이터를 확인하고,  
딥러닝 모델 입력 형태로 변환하는 전처리 과정을 구현했습니다.

**주요 내용**

- DICOM Header 및 Pixel Array 확인
- Rescale Slope와 Intercept를 이용한 HU 변환
- Soft Tissue 및 Lung Windowing
- 0–1 정규화 및 224 × 224 크기 변환
- 3-Channel 변환 및 ImageNet 정규화
- PyTorch 모델 입력 Tensor 생성

**기술**

`Python` `pydicom` `PyTorch` `NumPy` `Matplotlib`

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/ct-dicom-preprocessing)

---

### 6. Fertility Treatment Pregnancy Success Prediction

난임 시술 데이터를 이용하여 임신 성공 가능성을 예측하고,  
SHAP을 통해 주요 예측 변수를 분석했습니다.

**주요 내용**

- LightGBM·XGBoost·CatBoost 모델 비교
- 난임 도메인 기반 Feature Engineering
- Stratified Cross Validation 및 Optuna 최적화
- Feature Importance 및 SHAP 기반 모델 해석
- 해석 가능한 최종 22개 Feature 선정
- 임신 성공 확률 예측 결과 생성

**기술**

`LightGBM` `XGBoost` `CatBoost` `SHAP` `Optuna`

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/fertility-treatment-pregnancy-success-prediction)

---

## 기타 헬스케어 데이터 프로젝트

### Wearable Biometric Risk Monitoring

SQLAlchemy Core와 PyMongo를 활용하여 웨어러블 생체신호 데이터를  
MySQL과 MongoDB에 저장하고 위험 이벤트 발생 패턴을 분석했습니다.

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/wearable-biometric-risk-monitoring)

### Healthcare SQL High-risk Patient Analysis

환자·진단·방문 테이블을 설계하고,  
JOIN과 집계 함수를 활용하여 조건 기반 고위험 환자 데이터를 분석했습니다.

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/healthcare-sql-high-risk-patient-analysis)

### Smoking Status Health Analysis

흡연자와 비흡연자의 건강 지표를 비교하고,  
데이터 시각화·상관관계 분석·통계 검정을 수행했습니다.

🔗 [프로젝트 저장소](https://github.com/sanghyunkim-ai/smoking-status-health-analysis)

---

## 학력

### 아주대학교

- 의생명과학과 석사
- 연구 수행: 아주대학교 피부과학교실
- 2023.02 – 2025.02

### 목포대학교

- 생명과학과 학사
- 2011.03 – 2019.08

---

## 연구 및 실무 경력

### 난임연구소 연구원 | 서울라헬여성의원

2025.03 – 2025.11

- 사람 유래 검체 취급
- 정자 검사 및 결과 확인
- 인공수정 관련 연구 및 실무 참여

### 난임연구소 연구원 | 분당차병원

2026.01

---

## 교육 및 훈련

### Healthcare AI Bootcamp

2026.04 – 현재

- 헬스케어 데이터 분석
- 머신러닝 및 딥러닝
- 의료영상 AI
- SQL 및 데이터베이스
- Git과 GitHub
- FastAPI 및 Docker 기반 개발 환경 학습

---

## 연구 경험

### 피부세포 노화 및 색소 형성 연구

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

**Inhibitory Effects of CXCR4-specific SDF-1 Peptide  
(DGKPVSLSYR) on Melanogenesis in Human Melanocytes**

### 학술 발표

**Autophagy Dysfunction in Senescent Melanocytes:  
Impact of Melanin Accumulation and Subsequent ROS Generation**

제31회 대한피부과학연구학회 연례학술대회, 2024

### 특허 출원

**CXCR4 특이적 SDF-1 Peptide의 피부 미백 효능**

- 피부 색소 형성 억제용 조성물

---

## 자격 및 어학

- 정보처리기사 필기 합격 · 실기 준비 중
- 컴퓨터활용능력 2급
- OPIc IM1
- TOEIC Speaking IM2

---

## Contact

📧 tjdfud5759@naver.com  
🔗 [GitHub](https://github.com/sanghyunkim-ai)
