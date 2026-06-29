# Apartment Price Regression

아파트 특성 정보를 이용해 거래금액을 예측하는 회귀 프로젝트입니다.

## Problem

`전용면적`, `층`, `연식`을 바탕으로 `거래금액(만원)`을 예측합니다. 회귀 모델의 결과를 R2뿐 아니라 MAE/RMSE처럼 실제 금액 단위의 오차로 해석하는 데 초점을 두었습니다.

## Data

- Rows: 679
- Features: `전용면적`, `층`, `연식`
- Target: `거래금액(만원)`

## Models

- Linear Regression
- Ridge Regression
- Lasso Regression

## Evaluation

- MAE
- RMSE
- R2 Score
- Actual vs Predicted plot

## What This Shows

- 회귀 문제 정의와 오차 해석
- 기본 선형 회귀와 정규화 모델 비교
- feature 한계 분석과 개선 방향 도출

## Files

- `apartment_price_regression.ipynb`: 정리된 분석 노트북
- `data/Apartment_Data.xlsx`: 분석 데이터
