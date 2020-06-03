이 저장소는 부스트코스에서 파이썬으로 시작하는 데이터 사이언스 강의::([박조은](https://github.com/corazzon)) 를 실습한 내용입니다.

아나콘다 환경에서 파이썬3과 주피터노트북을 이용합니다.

사용한 라이브러리는 다음과 같습니다.

- numpy
- ㄴpandas
- matplotlib.pyplot
- seaborn

실습한 내용은 다음과 같습니다.

- 그룹화
  - value_counts는 1개의 Column 에 대해 그룹화합니다. 
  - groupBy와 pivot_table은 2가지 이상의 칼럼에 대해 그룹화합니다.
- classfication by groupby or pivot_table
  - groupby result is equivalent to using pivot_table
  - but  groupby more fast than 
- 히스토그램(pandas)

- seaborn

  - Countplot
    - 칼럼별 unique한 값에 따른 record의 총 개수
    - 카테고리형 데이터에 따른 record의 빈도 수 (수치형 데이터)
  - barplot
    - ci로 신뢰구간을 설정할 수 있음(기본 : 95%)
    - 카테고리형 데이터에 따른 수치형 데이터
  - lineplot
    - 카테고리형 데이터에 따른 수치형 데이터
    - 표현된 수치는 평균값임
    - 표준편차가 그래프에 표현됨
  - pointplot
  - boxplot
    - 이상치 확인에 좋습니다.
  - violinplot
    - boxplot의  box 내부를 표현해줍니다.
  - swarmplot

  - scatterplot
    - 수치형데이터와 수치형데이터의 표현
  - lmplot
    - 회귀선이 있습니다.
    - col 설정을 통해 다양하게 분석할 수 있음
  - distplot
    - 도수분포표
    - 히스토그램
    - 시리즈 형태의 데이터를 표현
    - 
  - hitmap
    - 상관관계 분석

- 이상치 다루기

  - 논리 연산으로 이상치 제외한 dataframe을 생성



이런 분들에게 이 저장소를 추천합니다.

- 기초 데이터분석 실습해보고 싶으신 분
- 분석하고 싶은 데이터의 형태에 따른 그래프의 선택 방법을 배우고 싶으신 분
- 이상치를 다룰 수 있는 방법을 배우고 싶으신 분



데이터 출처

[건강검진정보(2017)](https://www.data.go.kr/data/15007122/fileData.do#layer_data_infomation)