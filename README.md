# 서울특별시 아파트 실거래가 예측

## Dataset
1. apt.csv : 아파트 매매 실거래가 [국토교통부 실거래가 공개 시스템]
2. day_care.csv : 서울시 어린이집 정보 [서울 열린데이터 광장]
3. park1.csv : 서울시 공원(1인당 공원면적)통계 [공공데이터 포털]
4. apartment_price.csv : 데이터들을 전처리 후 저장한 최종 테이블  


## Coding
1. data_cleansing.ipynb
   - apt, day_care, park1 테이블 변수들을 정리 후 apartment_price 파일로 저장 
2. EDA_and_modeling(1).ipynb 
   - EDA
   - Linear Regression, Polynomial Regression, Ridge, Lasso, ElasticNet, 
     Decision Tree Regressor, Random Forest Regressor, Gradient Boosting
3. modeling(2).ipynb
   - Random Forest Regressor, Voting Regressor
4. modeling(3).ipynb
   - Bagging Regressor
5. modeling(4).ipynb
   - Linear SVR
6. apartment_price_final.ipynb
   - Best Model Test : Gradient Boosting
   - Rest Model Test : Linear Regression, Polynomial Regression, Ridge, Lasso, ElasticNet
                       Decision Tree Regressor, Random Forest Regressor, Linear SVR
                       
## Scoring by : mean squared error (MSE)
