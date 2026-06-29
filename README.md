# Apartment Price Regression

아파트의 전용면적, 층, 연식을 이용해 거래금액을 예측한 회귀 프로젝트입니다. 복잡한 모델을 쓰기보다, 해석하기 쉬운 선형 회귀 계열 모델을 비교하면서 어떤 변수가 가격 예측에 영향을 주는지 확인하는 데 초점을 뒀습니다.

## 문제 정의

아파트 기본 특성을 바탕으로 `거래금액(만원)`을 예측합니다.

- Rows: 679
- Features: `전용면적`, `층`, `연식`
- Target: `거래금액(만원)`

## 분석 흐름

- 데이터 구조와 기초 통계량 확인
- 전용면적, 층, 연식과 거래금액의 관계 시각화
- Train/Test split
- Linear Regression, Ridge, Lasso 모델 비교
- MAE, RMSE, R2 Score로 성능 확인
- 실제 가격과 예측 가격 산점도 비교

## 사용 모델

- Linear Regression
- Ridge Regression
- Lasso Regression

## 사용 기술

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 파일 구성

```text
apartment_price_regression.ipynb
data/
  Apartment_Data.xlsx
```

## 정리

이 프로젝트는 부동산 가격 예측 문제를 가장 기본적인 변수부터 시작해 모델링한 작업입니다. 데이터가 크지는 않지만, 실제 금액 단위의 오차를 MAE와 RMSE로 해석하면서 회귀 모델 결과를 어떻게 읽어야 하는지 정리했습니다.

추가로 개선한다면 역세권, 지역, 세대 수, 건축 연도, 거래 시점 같은 변수를 넣어 설명력을 높일 수 있습니다.

