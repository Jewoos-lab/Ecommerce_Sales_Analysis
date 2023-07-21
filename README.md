# E-commerce_Sales_Analysis
📊 Tableau를 활용한 전자상거래 판매 분석
<div align="center">
  <h1>📝 Tableau 활용 개인 프로젝트<br><br>
  💰 전자상거래 판매 분석</h1>
</div>

<h4> 💭 Language : SQL <br><br>
     🛠  Tool : MariaDB, Tableau <br><br>
     📅 진행기간 : 2023.06.23 ~ 2023.06.30</h4>
     
<br>

# 💡 분석 기획
* 터키의 고객 쇼핑데이터를 활용<br>
* SQL을 사용하여 분석에 필요한 데이터 추출 및 가공<br>
* 추출 및 가공한 데이터를 기반으로 Tableau를 사용하여 시각화 진행<br>
* 판매 수익, 이전 달로부터의 판매 성장률, 가장 많이 팔린 상위 5개의 제품, 거래량 추세, 나이별 판매 수익량 등을 분석<br>
* 터키의 전자상거래 판매 데이터를 Tableau로 나타낸 시각화를 기반으로 데이터 분석하여 새로운 인사이트 도출<br><br>

<br>

# 🔥 목적 및 필요성
* 고객이 필요로 하는 제품이나 서비스 사전 인지
> - 고객들이 주로 많이 구매하는 제품을 사전에 파악하여 제품 수량 대비 가능
> - 고객들이 주로 찾는 서비스를 사전에 파악하여 판매 전략 계획 가능
* 판매 성장률 비교를 통한 발전 
> - 높은 성장률을 가진 달의 특징과 낮은 성장률을 가진 달의 부족한 점을 보완하여 판매 계획 발전에 기여
* 고객 특징별 판매 전략 수립
> - 나이별, 성별 등 다양한 특징들에 대한 분석을 통해 새로운 판매 전략 계획 수립 가능<br> 
<br>


# 🔎 데이터 수집
|데이터셋|출처|
|------|:------:|
|고객쇼핑데이터|Kaggle|

<br><br>

# 📊 EDA(탐색적 데이터 분석)
## 1) 판매 수익, 거래량, 총량
<h3 align="center"><img src= "https://github.com/LHG-Git/E-commerce_Sales_Analysis/assets/100845169/147799ca-1f5b-4d43-9191-15a77ec31f38"></h3>

* Year, Month, Payment Method, Shoping Mall 별 판매 수익, 거래량, 총량 값을 나타내도록 필터를 생성<br>

<br><br>

## 2) 연월별 판매 거래량 추세
<h3 align="center"><img src= https://github.com/LHG-Git/E-commerce_Sales_Analysis/assets/100845169/90618478-a5be-4b42-b33d-3e461ffda495></h3>

* 거래량이 3000 ~ 4000 사이를 벗어나지 않아 안정적인 거래량을 띰<br>

* 2021년과 2022년 2월에만 거래량이 급감을 하였다가 다시 회복함<br>

* 2월달에 어떠한 이유로 거래량이 줄어드는지 추가 분석이 필요함<br>

<br><br>

## 3) 판매 수익률이 가장 높은 상위 5개 제품
<h3 align="center"><img src= https://github.com/LHG-Git/E-commerce_Sales_Analysis/assets/100845169/01e485a8-735c-4aab-996f-5e3bd9cfda74></h3>

* Clothing-1, Clothing-6941, Shoes-1, Technology-1, Shoes-2014에 해당하는 제품들이 수익률이 가장 높은 상위 5개 제품에 해당됨<br>
* 옷과 신발 등의 의류 제품들이 수익률이 높다는 것을 확인할 수 있음<br>

* 의류 품목을 주된 제품으로 선정한다면 보다 높은 수익률을 얻을 수 있음<br>

* 반면, 기술관련 제품은 상위 5개 제품들 중 1개밖에 해당하지 않기 때문에 새로운 판매 전략 기획 필요<br>

* 추가적으로, 기술관련 제품 뿐만 아니라 다른 제품들도 새로운 판매 전략 기획 필요 <br>

<br><br>

## 4) 판매 성장률
<h3 align="center"><img src= https://github.com/LHG-Git/E-commerce_Sales_Analysis/assets/100845169/c264cdba-16d4-4fcb-8e50-48034b2d37a6></h3>

* 2021년에는 3월부터 성장률이 회복되었다가 6, 8, 9, 11월에 성장률이 급감<br>

* 성장률이 급감했을때의 원인을 파악하는 것이 중요<br>

* 2022년도 마찬가지로 성장률 급감 원인을 파악하고 보완해가는 과정 필요<br>

<br><br>

## 5) 나이에 의한 판매 수익
<h3 align="center"><img src= https://github.com/LHG-Git/E-commerce_Sales_Analysis/assets/100845169/8e3f5af7-2a4e-4f3e-a51f-d38d54524da5></h3>

* 돈을 벌지 않는 청소년 고객은 다른 나이대 고객보다 적은 판매 수익을 띰<br>

* 노년기와 중년기의 고객의 판매 수익은 비슷<br>

* 좀 더 젊어 활동적인 중년기 고객들의 판매 수익이 노년기의 고객들보다 좀 더 높음<br>

<br><br>

## 6) 최종 대시보드
<h3 align="center"><img src= https://github.com/LHG-Git/E-commerce_Sales_Analysis/assets/100845169/79da6ce1-a008-4d3c-8813-a84bcd3775da></h3>

[태블로 바로가기] : https://public.tableau.com/app/profile/heegu.lee/viz/EcommerceSalesanalysis/1
