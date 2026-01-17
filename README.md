# 🌱 2024 Seoul Big Data Campus Competition – Green Store Priority Location Analysis in Seoul

This project was submitted to the **2024 Seoul Big Data Campus Competition** and is a **clustering-based location analysis project using Seoul public data**.
  
We conducted a data analysis to **derive priority location candidates based on demand for green stores and spatial characteristics**.
<br/>
<br/>

## 🔍 What We Did
- Integrated public data at the district (gu) level
- Performed EDA based on spatial, population, and commercial variables
- Applied multiple clustering methods  
  - K-Means  
  - K-Medoids  
  - Hierarchical Clustering  
  - GMM
- Selected target clusters using Hard Voting
- Calculated a Green Index (out of 100) and derived location candidates
<br/>
<br/>

## 📊 Data

### Cleaned Data Columns
- Seoul floating population / resident population  
- District-level commercial index  
- Large-scale mart licensing information  
- Green store status  
- Recycling index  
<br/>

### Data Sources
| Source | Dataset | Link |
|--------|--------|--------|
| Seoul Open Data Plaza | Seoul Floating Population by District (Domestic) | https://data.seoul.go.kr/dataList/OA-15439/S/1/datasetView.do |
| Seoul Open Data Plaza | Legal-dong Code Information from Building Register | https://data.seoul.go.kr/dataList/OA-15410/S/1/datasetView.do |
| Seoul Open Data Plaza | Seoul Commercial Analysis Service (Estimated Sales by District) | https://data.seoul.go.kr/dataList/OA-22176/S/1/datasetView.do |
| GitHub | Administrative District Boundary Geo Data | https://github.com/datainworld/administrative_district |
<br/>
<br/>

## 🛠 Tech Stack
- Python  
- pandas, numpy, scikit-learn  
- Jupyter Notebook / Google Colab  
- GeoJSON-based map visualization  
<br/>
<br/>
