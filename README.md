# *Project _ Bluehouse*
## **청와대 민원게시판 빅데이터 분석을 통한 경제 동향 파악**

한국외대 문화데이터포트폴리오 _ 손영준

문송한 과거에서의 첫 발걸음

학번 : 201501658

이름 : 손영준

:tv: 발표영상 링크 [https://youtu.be/VxGYRp8ID20]URL





### 1. 개요 및 요약
 [배경 및 목표]
  >본 리서치는 추후 경제 동향을 파악 하고자 하는 여러 이해관계자들의 수요를 인식하여 조사 및 분석을 진행하였습니다.
  많은 국민들이 자신의 의견을 피력하는 장소로 '청와대 민원 게시판'을 이용하기 때문에, 해당 보고서는 청와대 민원
  게시판의 Raw Data를 기반으로 국민 여론과 경제 동향을 파악하고자 하였습니다.

  [방법]
   >기본적으로 Google Colab 기능을 통하여 청와대 민원 게시판의 빅데이터를 추출하였고, 이를 형태소 분석기인
   Konlpy를 통해 해석하였습니다.
   
   
   
   
   
   
   
   
   
----








### 2. 분석 과정

 [데이터 스키마]
 
 아래와 같은 6가지의 카테고리를 CSV 형태로 추출
 
 <img width="520" alt="12" src="https://user-images.githubusercontent.com/74249464/102789564-a7ffd600-43e7-11eb-8ded-d74fe2a48fa9.png">



[데이터 분석 _ konlpy]

CSV 형태로 도출해낸 Raw Data를 엑셀로 가공하여 Pivot으로 분석하는 과정을 거쳤습니다.

Pivot으로 분석 중, 오른편과 같이 상대빈도수를 활용하여 형태소의 노출 빈도를 파악하여 그 중요도를 추론해내었습니다.

<img width="520" alt="12" src="https://user-images.githubusercontent.com/74249464/102790058-4b50eb00-43e8-11eb-8c89-54bde8a2c3d1.png">












----







### 3. 분석 결과

[명사]

<img width="520" alt="Noun" src="https://user-images.githubusercontent.com/74249464/102790537-ecd83c80-43e8-11eb-8edd-55fe84f4d2ec.png">




[기타 형태소]


<img width="520" alt="Other pos" src="https://user-images.githubusercontent.com/74249464/102790714-3b85d680-43e9-11eb-870c-aa6d60c0a4fc.png">







----


### 4. 결론

<img width="520" alt="Other pos" src="https://user-images.githubusercontent.com/74249464/102790868-78ea6400-43e9-11eb-9e66-83ae7d5fd6d7.jpg">


----

#### Author

 + :flag: South Korea
 * :School: HUFS
 
