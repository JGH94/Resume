#  분석하고 성장하는 개발자 정근화

### 정근화

- BLOG : https://we-co.tistory.com/
- GitHub : https://github.com/jgh94
- E-MAIL : jgh910000@naver.com

<br>

## 목차

* [경력](#경력)
  * 한국정보기술단 - 2023.05 ~ [ 현재 ]
  * 트라이업 - 2022.04.11 ~ - 2023.04.11
  * 비트컴퓨터 - 2019.01.02 ~ 2021.05.31
   
* [개인 프로젝트 및 작업](#개인-프로젝트)
  * Python
    - SSA에서 제공하는 이름 데이터 분석
    - Bit.ly와 USA.gov의 사용자 정보 분석
    - Tensorflow GPU 환경 구축 후, 모델 학습 진행
  * Spark
    - [Hyperparameter Tuning - Bayesian Oprimization](https://we-co.tistory.com/109)
    - [Pyspark Xgboost - Spark, MLlib Pipelines, 수요 예측](https://we-co.tistory.com/108)
  * C#
    - 판매 데이터를 분석하여 재고 추천 및 자동구매
* [회사 프로젝트](#회사-프로젝트)
  * Python
    - KS_AIus_DQ ( GS 인증 획득 )
    - 사내 RAG 구현
  * C#
    - MotionE
    - JPharm
* [기타](#기타)
    - Kaggle 분석 ( 타이타닉, 집값 예측하기 )
    - tensorflow Object detection api model
    - YOLO 논문
    - Pands, Matplotlib
    - 프로그래머스, 백준
<br>

## 경력
[한국정보기술단](http://www.audit.co.kr/news/)
* 2023.05 ~ [ 현재 ]

[트라이업](https://triupcorp.com/)
* 2022.04 ~ 2023.04  

[비트컴퓨터](https://www.bit.kr/)
* 2019.01 ~ 2021.05
 
<br>


# 프로젝트
## 개인-프로젝트
## 개인 프로젝트 및 작업 ( Python, C# )
### [ SSA에서 제공하는 이름 데이터 분석 ](https://github.com/JGH94/python_BabyName)
 https://www.ssa.gov/ 에서 제공하는 데이터를 분석하여 그 시기에 유행했던 이름, 추세를 시각화하는 작업
<br>
* 기간 : 2022.12 ~ 2022.12
* 소속 : 개인
* 역할 : Python, 데이터 수집
* 사용기술 : Python, Pandas, Numpy, Matplotlib
<div>    
 
<img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207745984-b7314ffe-77c7-4311-912b-b560065763f4.png">
<img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207746028-27f97135-d668-4118-adb5-c7342ad0bda1.png">

<img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207746069-ec569317-b6f8-45f2-8c8d-b5a53be9b861.png">  
<img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207746172-bd8b31ba-21b5-4087-8b61-468d3e1441bb.png">  
</div>
<br>


### [Bit.ly와 USA.gov의 사용자 정보 분석 ](https://github.com/JGH94/Python_BIT_USA)
 https://www.ssa.gov/ Bit.ly와 USA.gov에서 사용된 사용자들의 정보의 데이터를 분석하고 시각화
<br>
* 기간 : 2022.11 ~ 2022.11
* 소속 : 개인
* 역할 : Python, 데이터 적용 및 시각화
* 사용기술 : Python, Pandas, Numpy, Matplotlib
<div>     
<img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207747668-e6723bdd-87a7-498b-8595-20e88e20762d.png">
<img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207747713-baeb94b4-0ba6-44fd-badf-4f19d531e52a.png">
  
</div>
<br>


### 판매 데이터를 분석하여 재고 추천 및 자동구매 
  약품 판매 데이터를 분석하여 현재 재고를 통해서 필요한 개수를 추천해 주고, 크롤링을 통해 자동구매 프로그램 
<br>

* 기간 : 2021.3 ~ 2021.12
* 소속 : 개인
* 역할 : C#, Python 개발
* 성과 :
  - 자동사입 파이프 라인 구성, 인건비 절약
* 사용기술 : C#, MSSQL, Python, Selenium
  
<div>          
<img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207749957-4d61e3b9-16de-4147-abc6-87b1d0d4240d.png">
<img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207749848-e54a73a6-4cd2-42d6-ad29-fdc723ecb827.png"> 
</div>
<br>

## 회사 프로젝트 
<div>
  <img width="10%" height = "40dp" alt="image" src="https://github.com/JGH94/Resume/assets/41178868/2fa822fc-b82a-4ddb-9bee-19b31e12c3af"> 
</div> 
 데이터 댐 사업의 데이터를 정확성, 다양성, 개인정보 비식별화 등  데이터가 개방되기 전 검사를 진행하는 솔루션
<br>

* 기간 : 2023.05 ~ 개발 중
* 소속 : 한국정보기술단
* 역할 : Python 개발자
  - GS 인증 획득
  - 대용량 데이터 품질 점검 (정형, 비정형)
  - ElasticSearch 구조 설계 진행, 기존 데이터 적재량 대비 3배 이상 증가
  - 트래픽 모니터링을 위한 Kibana 연동 및 관리, 장애율 15% 감소
  - Docker 환경 컨테이너 운영 및 관리 with Jenkins
  - 이미지, 영상 객체인식 개인정보 검출 개발, 약 3만건 검출 

* 사용기술 : Python, Django, Elasticsearch, Kibana, Docker, Jenkins

<div>        
 <img width="35%" height = "220dp" alt="image" src="https://github.com/JGH94/Resume/assets/41178868/31efd54c-a08e-465b-a1e5-c8cbfa82b1ed"> 
 <img width="35%" height = "220dp" alt="image" src="https://github.com/JGH94/Resume/assets/41178868/eb884bb1-5314-4d42-b103-3bc47984196c">

</div>



<div>
  <img width="10%" height = "40dp" alt="image" src="https://github.com/JGH94/Resume/assets/41178868/2fa822fc-b82a-4ddb-9bee-19b31e12c3af"> 
</div> 
사내 RAG 시스템 구현

* 기간 : 2025.05 ~ 개발 중
* 소속 : 한국정보기술단
* 역할 : Python 개발자
  - LangChain 파이프라인 설계 및 개발
  - 문서 검색 및 인원관리 효율성 증가
  - OpenAI 및 Langfuse 연동 관리

* 사용기술 : Python, React, LangChain, OpenAI

<div>        
 <img width="50%" height="300dp" alt="image" src="https://github.com/user-attachments/assets/08f1a395-0cf8-4593-9cdc-c0b511b7f296" /> 
</div>

<br>





<div>
 <img width="10%" height = "40dp" src="https://user-images.githubusercontent.com/41178868/207754942-7bc482a5-792d-4972-aea2-90ef9f593dbc.png"> 
</div> 
병원 차트 프로그램으로 EMR, CRM 등 뷰티를 중점인 병원을 타겟인 프로그램
<br>

* 기간 : 2022.04 ~ 2023.04
* 소속 : 트라이업
* 역할 : C# 응용 SW 프로그램 개발, Web, Android 연동
* 사용기술 : C#, Json, CefSharp
  
<div>      
 <img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207752093-029a38a6-f099-453d-a914-5b18ecc28774.png">
 <img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207752159-9cd75f51-46ca-4244-b237-6295706d8d68.png"> 
 <img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207752249-8cfe213a-b287-443a-a18a-5a77cf547d71.png">  
 <img width="35%" height = "220dp" src="https://user-images.githubusercontent.com/41178868/207752354-62f9162b-2f6c-49f7-863d-b31d8e91870b.png">  
</div>
<br>


<div>  
<img width="10%" height = "40dp" src="https://user-images.githubusercontent.com/41178868/208035086-a74754bd-614a-4b6e-9f25-542683dd99ff.png"> 
</div> 
 약국을 타겟으로 개발된 프로그램, 라벨 프린터, 약가 등 약품에 대한 개발 진행
<br>

* 기간 : 2019.01 ~ 2021.05
* 소속 : 비트컴퓨터
* 역할 : C# 응용 SW 프로그램 개발, 타 업체와 개발 진행( KT, Pildoc )
* 사용기술 : C#, Json, MsSQL

<div>       
<img width="40%" height = "240dp" src="https://user-images.githubusercontent.com/41178868/208034877-cc6d5523-c31f-4c54-983b-8523175db6b5.png">
</div>
<br>


## 기타
* [Kaggle 분석 ( 타이타닉 )](https://github.com/JGH94/Kaggle_Titanic)
* [tensorflow Object detection api model](https://github.com/JGH94/Tensorflow_Detection_Model_ZOO)
* [YOLO 논문](https://we-co.tistory.com/category/YOLO)
* [Pands](https://github.com/JGH94/Python_Pandas),  [Matplotlib](https://github.com/JGH94/python_MatplotLib)
* [프로그래머스](https://github.com/JGH94/programers_code),  [백준](https://github.com/JGH94/BaekJoon_Code)


[ 자세한 이력서 ] (http://naver.me/5i0T70Xv)
