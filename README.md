# Python_API_Crawling_Project
# Python_API_Crawling_Project_전세가격_종속변수_독립변수

# 주택 전세 가격과 경제 변수간의 관계
## 한국은행 Open API를 이용한 데이터 수집 및 시각화

최근 주택 전세 가격 하락에 대한 뉴스를 쉽게 접할 수 있다. 데이터 분석으로 활용할 수 있는 주제로, 주택 전세 가격에 영향을 미치는 변수들을 찾고자 했다. 관련 내용 탐색 중, "한국건설관리학회 논문집 제13권 제2호 2012년 3월"에 실린 "주택 전세가격과 거시경제변수간의 관계연구"를 확인할 수 있었다.

<br>

논문 내용을 토대로 다음과 같은 데이터 분석을 실시하고자 했다. 먼저, **주택 전세가격** data와 그에 영향을 미치는 주택 수요자 중심의 요소 네가지, 즉 **가계 대출금리, 가계 예금총액, 주택 매매가격, 취업자 수** data가 있다. 논문에서는 2007년에서 2012년까지 데이터를 기반으로 회귀분석 기법을 통해 분석했다. 이에 따라, 2000년부터 최근 2022년까지의 논문 조사 기간을 포함한 데이터와 그에 따른 상관관계를 직접 시각화를 통해 확인해보고자 했다.

<br>

해당 data set들을 Open API, data crwaling 등의 기법으로 데이터를 모았다. 그리고 각각의 데이터가 실제로 "주택 전세가격"에 영향을 미치는 지 확인할 수 있도록 DataFrame화 한 뒤, 데이터 시각화를 통해 데이터간 상관관계를 도출했다. 마지막으로 시각화 자료를 통해 이끌어낸 의견을 말하려 한다.

<br>

### Project contributor: 나정민, 도형준, 유하영, 장인성

- 나정민: "가계대출금리", "주택전세가격" data 수집, "결론" 작성

- 도형준: "가계예금총액" data 수집, data visualizaion

- 유하영: "주택매매가격" data 수집

- 장인성: "경제활동인구" data 수집, "서론 및 목차" 작성
