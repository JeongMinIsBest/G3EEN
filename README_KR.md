# 🌱 2024 서울시 빅테이터캠퍼스 공모전 - 서울시 녹색매장 우선 입지 분석
2024 서울시 빅테이터캠퍼스 공모전 제출작 서울시 공공 데이터 기반 클러스터링 입지 분석 프로젝트입니다. **녹색매장 수요 및 공간적 특성 기반 우선 입지 후보를 도출**한 데이터 분석을 진행했습니다.
<br/>
<br/>

## 🔍 What We Did
- 자치구 단위 공공데이터 통합
- 공간 · 인구 · 상권 변수 기반 EDA
- 다중 클러스터링 적용  
  - K-Means  
  - K-Medoids  
  - Hierarchical Clustering  
  - GMM
- Hard Voting으로 Target Cluster 선정
- 녹색지수 (100점 만점) 산출 및 입지 후보 도출
<br/>
<br/>

## 📊 Data

### 정제된 데이터 컬럼
- 서울시 생활인구 / 거주인구  
- 자치구 상권지수  
- 대형마트 인허가 정보  
- 녹색매장 현황  
- 재활용 지표  
<br/>

### 사용된 데이터 출처
| 출처 | 데이터명 | 링크 |
|--------|--------|--------|
| 서울 열린데이터광장 | 자치구 단위 서울 생활 인구(내국인) | https://data.seoul.go.kr/dataList/OA-15439/S/1/datasetView.do |
| 서울 열린데이터광장 | 서울시 건축물대장 법정동 코드정보 | https://data.seoul.go.kr/dataList/OA-15410/S/1/datasetView.do |
| 서울 열린데이터광장 | 서울시 상권분석서비스(추정매출-자치구) | https://data.seoul.go.kr/dataList/OA-22176/S/1/datasetView.do |
| GitHub | 행정구역 경계 공간정보 파일 | https://github.com/datainworld/administrative_district |
<br/>
<br/>

## 🛠 Tech Stack
- Python  
- pandas, numpy, scikit-learn  
- Jupyter Notebook / Google Colab  
- GeoJSON 기반 지도 시각화  
<br/>
<br/>
