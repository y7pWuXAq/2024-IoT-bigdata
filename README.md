# 2024-IoT-bigdata
2024년 IoT 개발자 과정 빅데이터 및 인공지능 학습 리포지토리


### DAY 01

#### 빅데이터 분석 및 AI
- 빅데이터를 사용하여 사회전반적인 문제, 현상, 원인, 해결점 등을 찾아가는 분석방법
- 사회전반에 모든 곳에서 활용 
    - ex) : 쿠팡에서 20대 중반 여자들이 선호하는(트렌드) 화장품
        - 쿠팡에 20대 중반 여자 : 회원정보 검색
        - 회원들이 검색한 내용중 화장품을 조회
        - 그 중에서 가장 많이 검색된 화장품 통계
        - 20대 중반 여자 회원이 로그인
        - 첫화면에 검색된 화정품 1~3위를 디스플레이

- 빅데이터?
    - Big Data : 디지털환경에서 발생하는 대규모 정형 도는 비정형 데이터
    - 3V : Volume(크기, 규모), Variety(다양성), Velocity(속도)
    - 5V(3V + ) : Veracity(진실성), Value(가치)
    - 7V(5V + ) : Validity(정확성), Volatility(휘발성 : 데이터가 얼마나 오래 저장, 사용되는지)

- 데이터냐?
    - 정보를 수집자료 잧체, 값, 총계 + Value > 정보(Infomation)

- 빅데이터 분석 순서 : 생성 > 수집 > 저장 > 분석 > 표현
    - 생성 : IoT 센싱값, (쇼핑몰, 포털 등) 빅데이터 플렛폼을 통해서 생성
    - 수집 : MQTT로 DB에 저장, 빅데이터 플렛폼(하웁, 카프카 등)에서 수집. 네트워크까지 포함
    - 저장 : 수집과 거의 동일, DB에 저장(카프카, 데이터마이닝, NoSQL 등)
    - 분석 : 통계적 분석, 탐색적 분석(EDA), 머신러닝, 딥러닝, 자연어처리, 패턴인식, 이미지 프로세싱, 분석툴(Spark, Tableau, MS PowerBI) 사용
    - 표현 : 인사이트 도출(시각화, 그리드)

- 데이터 분석 기초
    - 파이썬 - 외 R, 자바, C# 등 다른 언어로도 분석가능. 단, 파이썬 가장 쉽기때문에 많이 사용
    - 데이터 분석에 들어가는 라이브러리(모듈) 부터 학습
        1. 데이터 처리 - Numpy(수치해석, 계산), Pandas(데이터처리), Scipy(과학계산) ...
        2. 시각화 - Folium(지도), Matplotlib(차트), Seaborn(Matplotlib 고급화) ...
        3. 엑셀 - openpyxl(엑셀 처리)
        4. 크롤링 - Selenium(웹크롤링 자동화), BeautifulSoup(웹페이지 정제)
        5. 머신러닝/딥러닝 - Scikit-Learn(가장 간단한 머신러닝), MS CNTK, Theano, Keras(최초의 딥러닝), TensorFlow(제일유명, Keras포함), PyTorch(페이스북!)

- 빅데이터 학습
    - 실습자료, 파이썬 기본(패스), 빅데이터 분석 기초학습 
    - [넘파이](https://github.com/hugoMGSung/Iot-bigdata-2024/blob/main/day1/bda01_numpy_basic.ipynb)
    - [판다스](https://github.com/hugoMGSung/Iot-bigdata-2024/blob/main/day1/bda02_pandas_basic.ipynb)
    - [맷플롭립](https://github.com/hugoMGSung/Iot-bigdata-2024/blob/main/day1/bda03_matplotlib_basic.ipynb)



### DAY 02
- 빅데이터 학습
    - 기초학습, 크롤링 관련
    - 셀레니움 + 뷰티플수프 같이 진행    
    - [뷰티플수프](https://github.com/hugoMGSung/Iot-bigdata-2024/blob/main/day2/dba04_beautifulsoup_basic.ipynb)
    - [셀레니움](https://github.com/hugoMGSung/Iot-bigdata-2024/blob/main/day2/dba05_selenium_basic.ipynb)

- 빅데이터 실습
    - 스타벅스 입지 분석
    - [스벅입지분석](https://github.com/hugoMGSung/Iot-bigdata-2024/blob/main/day2/dba06_starbucks_analysis.ipynb)



### DAY 03
- 개인 토이프로젝트
    - 깃헙 리포지토리, 빅데이터, 머신러닝, 딥러닝 레퍼런스를 참조 -> 클로닝형태
    - 리포지토리 10개 정도 리스트업 또는 리포지토리 검색해서 진행

- 빅데이터 실습
    - 스타벅스 입지 분석(계속)
    - 지난주 최종으로 만든 데이터 csv파일 다시 로드
    - [스벅입지분석](https://github.com/hugoMGSung/Iot-bigdata-2024/blob/main/day3/dba07_starbucks_analysis.ipynb)



### DAY 04

### DAY 05