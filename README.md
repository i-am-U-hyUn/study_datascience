# **데이터 과학과 Python 프로그래밍**

이 저장소는 데이터 과학의 기초 개념, 인과 관계, 가설 검정, 예측 및 Python 프로그래밍 등을 포괄적으로 다루는 자료와 실습 노트북을 포함하고 있습니다.

---

## 📘 **주요 내용 개요**

### 1️⃣ **데이터 과학이란?**
- 데이터 과학은 **탐색(Exploration)**, **예측(Prediction)**, **추론(Inference)**을 통해 대규모 데이터로부터 유용한 결론을 도출하는 학문입니다.
- 주요 활동:
  - **탐색**: 데이터 시각화와 기술 통계를 통해 패턴을 파악.  
  - **예측**: 머신러닝을 활용해 알지 못하는 값을 예측.  
  - **추론**: 발견된 패턴과 예측이 얼마나 일반화될 수 있는지 분석.  
[상세 보기](what-is-data-science.md)

---

### 2️⃣ **인과 관계와 실험**
- 데이터 과학에서 **인과 관계(Causality)**는 단순한 연관성(Association)을 넘어, 하나의 처치(Treatment)가 결과에 미치는 직접적인 영향을 설명합니다.
- 관찰 연구(Observational Study)와 실험을 통해 데이터의 인과 관계를 분석하고, 보다 신뢰할 수 있는 결론에 도달합니다.  
[상세 보기](causality-and-experiments.md)

---

### 3️⃣ **Python 프로그래밍**
- Python은 데이터 수집, 분석 및 시각화를 자동화하는 강력한 도구입니다.
- 이 자료는 Python을 사용해 데이터를 조작하고, 통계 분석 및 머신러닝 모델을 구현하는 방법을 안내합니다.  
[상세 보기](programming-in-python.md)

---

## 💻 **주피터 노트북 주제별 설명**

이 저장소에는 다음과 같은 주제를 다루는 Jupyter Notebook이 포함되어 있습니다:

1. **기초 데이터 조작**  
   - **Data_Types.ipynb**: Python에서 다양한 데이터 유형 다루기  
   - **Sequences.ipynb**: 리스트, 튜플 등 시퀀스 타입 이해  
   - **Tables.ipynb**: 테이블 데이터 조작 및 분석  

2. **시각화와 데이터 분석**  
   - **Visualization.ipynb**: 데이터 시각화 기법  
   - **Functions_and_Tables.ipynb**: 함수와 테이블을 활용한 데이터 조작  
   - **Randomness.ipynb**: 난수 생성 및 활용  

3. **통계 및 가설 검정**  
   - **Testing_Hypotheses.ipynb**: 가설 검정의 원리와 적용  
   - **Comparing_Two_Samples.ipynb**: 두 샘플 간 차이 비교  
   - **Estimation.ipynb**: 점 추정과 구간 추정 이해  
   - **Why_the_Mean_Matters.ipynb**: 평균의 중요성과 데이터 중심성  

4. **머신러닝 및 예측**  
   - **Prediction.ipynb**: 머신러닝 기반 예측 모델 구축  
   - **Updating_Predictions.ipynb**: 새로운 데이터에 기반한 예측 업데이트  
   - **Classification.ipynb**: 분류 모델 구현  
   - **Inference_for_Regression.ipynb**: 회귀 분석 및 추론  

---

## 📂 **폴더 구조**

```plaintext
.
├── what-is-data-science.md                  # 데이터 과학 개요
├── causality-and-experiments.md             # 인과 관계와 실험
├── programming-in-python.md                 # Python 프로그래밍 소개
├── notebooks/
│   ├── Data_Types.ipynb                     # 데이터 유형
│   ├── Sequences.ipynb                      # 시퀀스 데이터
│   ├── Tables.ipynb                         # 테이블 조작
│   ├── Visualization.ipynb                  # 데이터 시각화
│   ├── Functions_and_Tables.ipynb           # 함수와 테이블
│   ├── Randomness.ipynb                     # 난수 생성
│   ├── Testing_Hypotheses.ipynb             # 가설 검정
│   ├── Comparing_Two_Samples.ipynb          # 샘플 비교
│   ├── Estimation.ipynb                     # 점 추정과 구간 추정
│   ├── Why_the_Mean_Matters.ipynb           # 평균의 중요성
│   ├── Prediction.ipynb                     # 예측 모델
│   ├── Updating_Predictions.ipynb           # 예측 업데이트
│   ├── Classification.ipynb                 # 분류 모델
│   └── Inference_for_Regression.ipynb       # 회귀 추론
```

---

## 🛠️ **설치 및 사용 방법**

1. **저장소 클론**  
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. **필수 패키지 설치**  
   필요한 Python 패키지를 설치합니다:
   ```bash
   pip install -r requirements.txt
   ```

3. **Jupyter Notebook 실행**  
   노트북 서버를 시작하여 자료를 확인합니다:
   ```bash
   jupyter notebook
   ```

---

## 📄 **참고 문서**

- 데이터 과학 및 Python 프로그래밍은 이론과 실습을 결합하여 강력한 분석 기술을 학습할 수 있도록 설계되었습니다.
