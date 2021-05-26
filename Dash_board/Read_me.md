# Burget_index Dashboard

### important packages

- flexdashboard : R markdown이 그대로 시각화되는 레이아웃
<br>

- shiny : R markdown과 연계하여, interactive한 Dashboard를 만들 수 있는 package
<br>


### 실행순서

- code 파일내 모든 파일이 반드시 한 폴더안에 존재하여야 함.
<br>

- burger_index.Rmd 파일 실행
<br>

- Dashboard를 확인하고 싶다면, R-studio 상단의 "Run Document" 실행
<br>

### Intro slide

![image.png](attachment:image.png)

- 버거지수와 인구수를 지도에 시각화하여 제시
<br>

- 2개를 비교하며, 버거지수에 대한 관심 환기
<br>

- 버거 지수에 대한 수식 설명

### Firtst slide

![image.png](attachment:image.png)

- 좌측 상단의 콤보박스를 이용하여, 광역시, 시, 군 단위로 버거지수 상위 10개 도시를 막대그래프로 확인 가능
<br>

- 우측에는 data_korea.xlsx에서 추출한 raw data 제시
<br>

- 우측 상단에서 도시명으로 버거지수 검색가능

### Second slide

![image.png](attachment:image.png)

- 각 햄버거 브랜드 별로 매장수를 막대그래프로 시각화
<br>

- 막대 그래프별로 광역시, 시, 군 각 도시군별로 분포된 매장 수 확인 가능
<br>

- 좌측에서 햄버거브랜드 및 도시군별 정확한 매장 수 확인 가능 


### Third slide

![image.png](attachment:image.png)

- 버거 지수가 유효한지 확인하기 위해 인구수와 회귀분석 실시
<br>

- 우측에서 R Studio로 분석한 결과 확인 가능
<br>

- 분석 결과 유효하며, 버거킹은 상업 및 인구 밀집 지역에만 분포
<br>

- 반면, 롯데리아는 주택가 근처에 광범위하게 분포하여 두 브랜드간의 입점 전략이 가장 상이함
<br>

### Forth slide

![image.png](attachment:image.png)

- 분석에 쓰인 raw data download url 제공
<br>

- 버거 지수와 인구수 raw data 확인 가능
<br>

- 좌측에서 Intro slide에서 작성한 지도의 파이썬 코드를 확인 가능 (= visualization>Burger_index>code)



```python

```
