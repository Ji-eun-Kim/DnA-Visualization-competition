# 서울특별시 자치구별 학구열 분석 및 사업 소개

<br/>

## 1. 배경 및 목적

- 서울특별시 자치구별 학구열 분석을 통한 교육사각지대 분석 및 인사이트 도출

<br/>

## 2. 주최 기관

- 주최: 2022 D&A Basic Session
- 순위: 2위 (13팀 중)
- 참가 인원: 60명 (13팀)

<br/>

## 3. 프로젝트 기간 
- 2022.05 ~ 2022.06 (2개월)


<br/>

## 4. 프로젝트 설명 

<img width="463" alt="시각화1" src="https://github.com/Ji-eun-Kim/ML-competition-in-kaggle/assets/124686375/bf29a9f7-330a-44ee-a008-28b5c09bac68"> <br/>
현재 우리나라의 교육 격차는 심각한 사회적 문제로 부각되고 있다. 특히 서울특별시의 자치구별 학교들 간의 교육 격차가 더욱 심하다는 문제를 해결하고자, 지역구 별 특징 분석 및 학구열 현황 등을 분석해보고 해결하기 위한 인사이트 도출 아이디어 제시 프로젝트를 진행하였다.
   데이터의 경우 **외부 데이터를 포함한 총 9가지의 데이터**를 활용하였다. **메인 데이터는 크게 4가지, 추가적으로 서브 데이터 4가지, 외부 데이터 1가지**를 종합하여 분석을 진행하였다. 5가지의 세부 주제를 정하여 각 주제에 맞게 데이터 분석을 진행하였다. 전처리의 경우, 데이터 별 분석을 통해 **결측치 처리, 중복값 제거, 이상치 처리**를 진행하였다.

<img width="557" alt="시각화2" src="https://github.com/Ji-eun-Kim/ML-competition-in-kaggle/assets/124686375/aafad9b5-a202-43ec-89f1-8001c44e7a89"><img width="557" alt="시각화3" src="https://github.com/Ji-eun-Kim/Big-Data-Processing-n-Visualization/assets/124686375/045cfc85-b4ea-487e-ba55-e429c9686c51">
<br/> 
주제 1의 경우, scatterplot, boxplot, pearson 상관계수 등을 활용하여 자치구별 학교에 다니는 학생 수 비율 및 자치구별 학원에 다니는 학생 수 비율을 분석하였고, 결과적으로 교육열이 낮은 자치구는 전 연령에서 동일한 낮은 교육열을 보였지만, 교육열이 높은 자치구는 연령에 따라 바뀐다는 인사이트를 도출하였다. 
<br/>
<img width="557" alt="시각화4" src="https://github.com/Ji-eun-Kim/Big-Data-Processing-n-Visualization/assets/124686375/eb41db69-9d19-4516-aef9-c3dc0873e813"><img width="560" alt="시각화5" src="https://github.com/Ji-eun-Kim/ML-competition-in-kaggle/assets/124686375/80d4ecc8-9273-447c-af94-f1cc39cd060d"><br/>
 주제 2의 경우, 데이터를 활용하여 강남 8학군은 실제로 학구열이 높을까?라는 의문에서 분석을 진행하였고, 결과적으로 8,9학군의 학원 학생 수가 다른 학군에 비해 압도적으로 많다는 것을 도출하였으며, 학교/학생 수 대비 학원/교습소 학생 수가 많다는 것을 도출하였다. 이를 통해 타 학군 소재 학교 학생들이 8,9학군 소재 학원에 등원함을 유추할 수 있다.
<br/>

<img width="557" alt="시각화6" src="https://github.com/Ji-eun-Kim/ML-competition-in-kaggle/assets/124686375/f736e0bf-bbc9-4de9-abab-8de253e5daed"><img width="557" alt="시각화7" src="https://github.com/Ji-eun-Kim/Big-Data-Processing-n-Visualization/assets/124686375/2a30b96c-8d1a-4d7f-ba7f-6e7dac0872f2"><br/>
 주제 3의 경우, grdp가 높은 자치구는 학구열이 높을까?라는 의문에서 분석을 진행하였고, 분석 및 시각화를 진행한 결과, 자치구별 grdp가 높은 곳(강남구,양천구,서초구)일수록 학교, 학원 및 교습소 수도 많다는 것을 도출하였다. 즉, grdp가 높을수록 학구열이 높은 경향을 보인다 라는 인사이트를 도출하였고, 학구열이 높은 7,8학군의 강남구, 서초구, 양천구는 입시, 검정 및 보습학원의 비율이 높았고, 중랑구의 경우 예체능 학원의 비율이 높다는 인사이트 또한 도출하였다.
 <br/>

<img width="559" alt="시각화8" src="https://github.com/Ji-eun-Kim/ML-competition-in-kaggle/assets/124686375/dea11930-8f06-473d-a487-bb002efbd617"><img width="557" alt="시각화9" src="https://github.com/Ji-eun-Kim/Big-Data-Processing-n-Visualization/assets/124686375/5bd006d2-f843-409f-9c17-af7148fccbbe"><br/>
  주제 4의 경우, 서울 외곽 지역에 학원 수가 많은 이유는? 이라는 의문에서 분석을 진행하였다. 결론적으로는 학령인구 수 상위 10개의 자치구 중 9군데가 외곽에 위치해 있으므로 외곽지역에 학령인구가 많다는 것을 도출하였고, 외곽 지역의 grdp가 다른 지역의 grdp보다 상대적으로 높다는 것을 도축하였다. 이는 소득수준이 높으면 학원에 많이 다니므로 소득이 높은 외곽지역에 학원 수가 많다는 것을 의미하였다.
<br/>

<img width="557" alt="시각화10" src="https://github.com/Ji-eun-Kim/ML-competition-in-kaggle/assets/124686375/68d93db7-e0db-400f-bd30-b5b14ac960fc"><img width="559" alt="시각화11" src="https://github.com/Ji-eun-Kim/Big-Data-Processing-n-Visualization/assets/124686375/342f20bc-d0f6-4caa-b95b-03bc10ffc87e"> <br/>
사교육열과 지역내총생산의 상관관계를 구한 결과, 자치구 전체를 살펴봤을 때 **사교육열과 지역내총생산(grdp)의 상관관계가 약 50% 정도로 낮은 상관관계**를 보였다. 또한 서울 **지역내총생산 상위 10% 자치구와 하위 10% 자치구**만 따로 뽑아서 상관관계를 구했더니 **78%라는** 값을 도출하였다. 이를 통해  지역내총생산이 평균인 지역들은 지역내총생산과 사교육열 간의 상관관계가 크지 않았지만 **지역내총생산이 매우 높은 지역일수록 사교육열이 더욱 높았**으며, 지역내총생산이 매우 낮은 지역일수록 사교육열이 줄어드는 것을 확인할 수 있었다. 

결론적으로, **지역내총생산이 가장 적은 강북구, 중랑구, 용산구는 교육사각지대로 볼 수 있었고,** 정부의 교육 지원이 필요하다고 판단하였다. 이에 학습 자원 접근이 어려운 청소년들을 대상으로 하는 교육 서비스 사업인 ‘서울런’의 홍보와 지원이 더 필요하다고 판단하였고, 이를 통해 **교육 격차의 해소**를 기대하며 프로젝트를 마무리하였다.



## 5. 팀원 및 담당 역할  

**<팀원>**

- 총 6명 (전공생 3명, 타과생 2명)

**<담당 역할>**

- 데이터 수집 및 전처리
- 자치구별 grdp 총 수와 자치구별 학교수의 상관관계 분석 및 시각화, 인사이트 도출

<br/>

## 6. 발표 자료 및 데이터

- 발표 자료  
https://github.com/Ji-eun-Kim/DnA-Visualization-competition
