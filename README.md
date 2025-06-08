# 💊 Pharmacology Simulations

이 프로젝트는 Python과 Jupyter Notebook을 활용해 **약리학(PK/PD)** 개념을 시각화하고 시뮬레이션한 포트폴리오입니다.  
기초적인 효소 반응부터 dose-response, 반복 투약, bioavailability까지 다양한 내용을 다룹니다.

---

## 📂 프로젝트 구성

### 1. `enzyme_simulation`
- **Michaelis-Menten kinetics** 시뮬레이션
- 경쟁적 & 비경쟁적 저해제 비교
- `ipywidgets`를 활용한 실시간 슬라이더 조절 기능

### 2. `dose_response`
- **Hill Equation** 기반 dose-response 곡선
- full agonist vs partial agonist
- competitive & noncompetitive antagonist 분석

### 3. `pharmacokinetics`
- 정맥투여(IV) vs 경구투여(PO)
- bioavailability (F), AUC 시각화
- 반복 투약 & steady-state 모델링
- loading dose & maintenance dose 계산

---

## 🛠 사용 기술

- Python 3.x
- Jupyter Notebook
- NumPy, Matplotlib
- ipywidgets (슬라이더 UI)
- Git / GitHub

---

## ✨ 목표

- 약리학 이론을 **직접 시각화하고 구현함으로써 더 깊이 이해**
- 파이썬과 약리학을 융합한 개인 프로젝트