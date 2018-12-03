<본 자료는 Data Visualization 과제 수행을 위해 **정보 디자인**에 대해 정리한 내용입니다.>

***

# 정보 디자인

## 정의
 - 효과적인 정보와 복잡하고 구조적이지 않은 기술 데이터를 시각적으로 표현하는 방법
 - 데이터 시각화, 정보 시각화도 정보 디자인 범위에 속하며, 그래픽 정보 표현 방법으로 많이 적용되는 인포그래픽 역시 정보 디자인의 한 유형으로 볼 수 있다.
 - 대규모 비수량 정보를 시각적으로 표현하는 것으로, 보는 이가 직관적으로 정보를 인지할 수 있게끔 시각적 표현 방법을 통해 제공한다.

## 예시
 **샤를 미나르의 나폴레옹 행군흐름도**
 - 지도 형식으로 표현되어, 이동흐름에 따라 나폴레옹 군대의 쇠락을 보여준다.
 - 병사의 수, 행군 중인 병사들의 지리적 위치, 각 위치에서의 기온과 같은 다차원 정보를 한눈에 볼 수 있다.
 - 이 그림은 모스크바에 도착했을 당시 나폴레옹 군대가 얼마나 약화되었는지, 추운 겨울이 군대 약화에 끼친 영향 등을 보여준다.

 ![Image of Minard](https://upload.wikimedia.org/wikipedia/commons/2/29/Minard.png)

**나이팅게일의 폴라 지역 다이어그램**
 - 나이팅게일은 폴라그래프를 통해 전쟁터에서 사망하는 병사보다 열악한 위생 환경으로 사망하는 병사가 많다는 사실을 표현하여, 정부를 설득하는데 활용했다.

 ![Image of Nightingale](http://img.hani.co.kr/imgdb/resize/2017/1022/00501712_20171022.JPG)

## 정보 디자인에서 빅데이터 시각화 영역
  - 데이터를 기반으로 **객관적인 표현**에 더 초점을 맞추는 경우가 많으므로 **정보형 메시지를 전달하기 위한 데이터 시각화 작업을 하는 경향**이 강하다. 양적 정보 디자인을 다루는 빅데이터 시각화에서는 정보의 내용과 환경이 매우 복잡하므로 표현도 다차원적이어야 한다.
  - **어떤 식으로 데이터를 해석하는가에 대한 통계적 차원의 시각화 방법 및 시각 표현이 병행**되어야 한다.


## 정보 시각화 프로세스
- **시각화 프로세스**
 - 정보 구조화  
 : 데이터를 수집하고 정제하는 과정으로 데이터셋을 만들기 위한 분석도구 필요
 - 정보 시각화  
 : 분석도구에서 제공하는 그래프나 분석도구 특성에 따른 시각화
 - 정보 시각표현  
 : 시각화의 의도를 강화해 전달하기 위해 분석도구에서 만든 결과물에 별도 그래픽 요소를 추가해 완성


- **벤 프라이의 시각화 방법론**

단계 | 세부단계 | 설명 | 관련 분야
------------ |------------ | ------------- | -------------
구조화 | 획득 | 정보 수집 | CS
구조화 | 분해 | 정보의 의미를 바탕으로 구조적으로 카테고리화 | CS
구조화 | 선별 | 1,2 과정을 바탕으로 의미있는 정보와 의미 없는 정보를 구분해 필요없는 정보를 제거 | CS,STATS,Mathematics
구조화 | 마이닝 | 과정의 데이터를 분석해 정보 추출 알고리즘을 도출 | CS,STATS,Mathematics
시각화 | 표현 | 4 과정을 통해 얻은 정보를 효율적으로 표현할 수 있는 방법에 대해 연구 | GD
시각화 | 정제 | 5 과정에서 도출한 규칙을 바탕으로 정보를 시각적으로 정제 | GD
시각표현 | 상호작용 | 앞 단계에서 얻은 정보를 다양한 시각에서 시뮬레이션 할 수 있는 방법을 반영 | HCI

### 시각화 기술의 종류

- 도표와 통계 분석 도구 (Charting and statistical analysis tools)  
 - eg. Microsoft Excel, Tableau
- 프로그래밍 환경 (Programming environment)
 - eg. D2.js, Processing, R ggplot2
- 전문가 도구 (Specialist tools)
 - eg. Adobe Illustrator, Adobe Effect, ArcGIS, Gephi

### 색채
 - 색상의 3요소 : 색상(Hue), 명도(Brightness), 채도(Saturation)
 - [색상환의 혼합색과 배색의 종류](https://static.wixstatic.com/media/e33834_7387d174977f4fb28a84315c18d8668d~mv2.jpg/v1/fill/w_487,h_307,al_c,lg_1,q_80/e33834_7387d174977f4fb28a84315c18d8668d~mv2.webp)
 - [D3.js에 내장된 색채 배합의 예](https://static.wixstatic.com/media/e33834_cca5743e80c84471975761dd54489f63~mv2.jpg/v1/fill/w_900,h_262,al_c,lg_1,q_80/e33834_cca5743e80c84471975761dd54489f63~mv2.webp)
 - [색채 배합 사이트](http://colorbrewer2.org)


### Chart
아래 단계에 따른 [그래프 특성 비교]()
- 비교 (Comparison)
- 관계 (Relation)
- 분산 (Distribution)
- 구성 (Composition)

## 참고자료
- [빅데이터 분석 시각화 분석](https://www.slideshare.net/neofuture/sds-n2), 이지선, slideshare
- D3.js 실시간 데이터 시각화, 파블로 나바로 카스틸로, 에이콘출판
- [송한나의 the art of data](http://www.dbguide.net/knowledge.db?cmd=view&boardUid=193099&boardConfigUid=19&boardStep=&categoryUid=$categoryUid), 송한나, 데이터전문가지식포털

## 별첨
 - [David McCandless, 시각적 이해 위계도](https://informationisbeautiful.net/2010/data-information-knowledge-wisdom/)

 ![Image of david](http://infobeautiful2.s3.amazonaws.com/data_info_knowledge_wisdom.png)
