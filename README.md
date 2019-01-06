# 데이터 시각화 정리


## 정보 디자인이란?
 * 효과적인 정보와 복잡하고 구조적이지 않은 기술 데이터를 시각적으로 표현하는 방법
     cf. [David McCandless, 시각적 이해 위계도](https://informationisbeautiful.net/2010/data-information-knowledge-wisdom/)

 * 정보 시각화, **데이터 시각화**도 정보 디자인 범위 속하며 **보는 이가 직관적으로 정보를 인지할 수 있게끔 시각적 표현 방법을 통해 제공**한다.

     > 전혀 기대하지 않은 것을 깨닫게 해줄 때 그림은 가장 가치있다.  
     > John W.Tukey, Exploratory Data Analysis



## 데이터 시각화란?

### 구성요소
  * **메신저 (=전달자, eg.디자이너)**
  * **수신자 (eg.독자, 사용자)**
  * **메시지 (=시각화된 데이터, eg.차트, 인포그래픽, 터치 스크린)**

### 단계
  * **데이터 형상화 (Representation)**
    * 물리적으로 데이터에 형태를 부여하는 과정
    * 시각 변수(Visual Variable)를 활용해서 차트, 그래프를 만드는 과정
  * **데이터 표현 (Presentation)**
     * 차트, 그래프 등에 색상 선택, 상호작용, 주석, 구성요소 배치 등을 적용하는 과정 (디자인 통합 과정)
  * **시지각 능력의 활용**
     * 눈과 뇌가 공간 추론, 패턴 인식 등 시지각 능력을 활용하여 정보를 처리하는 과정
  * **인지의 확장**
     * 수신자의 정보처리 과정을 극대화하는 것

### 예시
#### 샤를 미나르의 나폴레옹 행군흐름도
 * 지도 형식으로 표현되었으며 이동흐름에 따라 나폴레옹 군대의 쇠락을 보여준다.
 * 병사의 수, 행군 중인 병사들의 지리적 위치, 각 위치에서의 기온과 같은 다차원 정보를 한눈에 볼 수 있다.
 * 이 그림은 모스크바에 도착했을 당시 나폴레옹 군대가 얼마나 약화되었는지, 추운 겨울이 군대 약화에 끼친 영향 등을 보여준다.

![Image of Minard](https://upload.wikimedia.org/wikipedia/commons/2/29/Minard.png)

#### 나이팅게일의 폴라 지역 다이어그램
 * 나이팅게일은 폴라그래프를 통해 전쟁터에서 사망하는 병사보다 열악한 위생 환경으로 사망하는 병사가 많다는 사실을 표현하여, 정부를 설득하는데 활용했다.

 ![Image of Nightingale](http://img.hani.co.kr/imgdb/resize/2017/1022/00501712_20171022.JPG)

#### 앤스콤비의 콰르텟
 * 샘플 데이터 집합의 데이터 시각화 전후

 ![Image of Anscombes1](http://brianmc.dbsdataprojects.com/wp-content/uploads/sites/56/2016/02/original-281x300.jpg)
 ![Image of Anscombes2](https://upload.wikimedia.org/wikipedia/commons/e/ec/Anscombe%27s_quartet_3.svg)


## 시각화 방법

### 원칙
* **Good Case**
  * 시각화 디자인은 직관이나 본능에 의지하는 것이 아닌 **원칙**과 **의도**로 다뤄져야 한다.

  > 효과적으로 정보를 표현하는 기술은 직관이 아니라 학습을 통해 얻어진 원칙에 의해 습득된다.  
  > Stephen Few, Show me the Numbers


* **Bad Case**
  * 개인적인 취향에 기반한 디자인 스타일이 있다.
  * 마음에 드는 것이 본능적으로 떠오를 때까지 이것저것 시도한다.
  * 소프트웨어에서 제공하는 기본 디자인에 만족하고 더 수정하지 않는다.
  * 소프트웨어에 익숙하지 않아서 디자인을 수정하는 방법을 모른다.
  * 상사의 요구에 따른다. "멋진 차트를 만들어 주겠나?"


 ### 프로세스
 #### 벤 프라이의 시각화 방법론

 단계 | 세부단계 | 설명
 ------------ |------------ |------------
 구조화 | Acquire | 정보 수집
 구조화 | Parse | 정보 의미를 바탕으로 구조화(카테고리화)
 구조화 | Filter | 의미 없는 정보 제거
 구조화 | Mine | 데이터 분석을 통해 정보 도출을 위한 알고리즘을 도출
 **시각화** | **Represent** | **바, 라인, 트리 등 시각화 모델 선택**
 **시각화** | **Refine** | **명확하고 매력적으로 시각화 모델 개선**
 **시각표현** | **Interact** | **시각화 인터랙션 추가**

## 고려할 것
#### 1. 의도
 * 데이터 설명 (eg.샤를 미나르의 나폴레옹 행군흐름도, 나이팅게일의 폴라 지역 다이어그램)
 * ___데이터 탐색을 위한 수단으로 제공 (eg.앤스콤비의 콰르텟) ...아래 계속___
 * 표현을 위한 "전시" 목적


 * **탐색적 솔루션**
   * 사용자가 시각적으로 데이터를 탐색할 수 있는 인터페이스 역할
   * 사용자가 솔루션을 활용함으로써 호기심을 자극하고, 패턴이나 관계 등 새로운 발견 가능
   * 설명을 위한 시각화에 비해 인사이트를 얻기 위한 노력이 필요함
   * 정적 영역, 인터랙션 영역(필터링, 정렬, 브러싱, 변수 조정 등)을 분리하여 구현


#### 2. 편집방향
 * 시각화 작업을 하는 이유는 무엇인가?
 * 누구를 위해 작업하고, 요구사항은 얼마나 잘 정의되었는가?
 * 어떤 기능을 수행하는가?
 * 만들고자 하는 시각화는 어떤 톤(tone)인가?


#### 3. 시각화 디자인 옵션
 * 색상
   * 데이터의 정량적 표현을 위해서는 **순차적 색상 배합, 발산형 배합**을 사용한다.
   * 사람의 눈은 한번에 **최대 12개의 색상을 구분**할 수 있다.
   * 색맹, 색약을 고려하여 색상을 선택해야 한다.
   * 넓은 영역에는 강하고 채도가 높은 색상의 사용을 피하라. 대신 강조나 주의를 끌어야할 때 옵션으로 사용한다.
 * 인터랙션
 * 주석
 * 배치


### 분류 체계
[Hierarchy of visual understanding](https://freshpeel.com/2010/11/hierarchy-of-visual-understanding/)


## 시각화 기술의 종류
1. **도표와 통계 분석 도구 (eg. Microsoft Excel, Tableau)**
1. **프로그래밍 환경 (eg. D2.js, Processing, R ggplot2)**
1. **전문가 도구 (eg. Adobe Illustrator, Adobe Effect, ArcGIS, Gephi)**



## 참고자료
* 데이터 시각화 설계와 활용, 앤디 커크, 에이콘출판
* D3.js 실시간 데이터 시각화, 파블로 나바로 카스틸로, 에이콘출판
* [빅데이터 분석 시각화 분석](https://www.slideshare.net/neofuture/sds*n2), 이지선, slideshare
* [송한나의 the art of data](http://www.dbguide.net/knowledge.db?cmd=view&boardUid=193099&boardConfigUid=19&boardStep=&categoryUid=$categoryUid), 송한나, 데이터전문가지식포털

## 볼만한 자료
  * [색상환의 혼합색과 배색의 종류](https://static.wixstatic.com/media/e33834_7387d174977f4fb28a84315c18d8668d~mv2.jpg/v1/fill/w_487,h_307,al_c,lg_1,q_80/e33834_7387d174977f4fb28a84315c18d8668d~mv2.webp)
  * [D3.js에 내장된 색채 배합의 예](https://static.wixstatic.com/media/e33834_cca5743e80c84471975761dd54489f63~mv2.jpg/v1/fill/w_900,h_262,al_c,lg_1,q_80/e33834_cca5743e80c84471975761dd54489f63~mv2.webp)
  * [색채 배합 사이트](http://colorbrewer2.org)
