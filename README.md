# PythonProject

## 프로젝트 개요
코로나가 잠잠해지며 밖으로 나오는 사람들이 많아지고 이에 따라 외출 패션에 관심이 많아져 인기가 많은 패션에 대해 한눈에 볼 수 있도록 실시간 검색어 수집 후 축적된 검색어의 빈도수로 그래프 생성 및 워드클라우드 생성 및 저장할 수 있도록 했습니다.

## 요구사항 정의
- schedule과 BeautifulSoup을 사용하여 실시간 자동 수집
- 수집 기간: 10시~17시, 1시간마다 크롤링 진행(무신사 인기 검색어 페이지 1시간마다 갱신)
- 수집한 데이터를 txt 파일로 저장 
- 추출한 데이터를 기반으로 시각화 
 
- 수집한 인기 검색어 키워드 선택 시 브랜드 크롤링
- selenium을 이용하여 상품 브랜드 데이터 추출(최대 10페이지, 900개) 
- 추출한 데이터를 기반으로 시각화
## 프로젝트 결과
### 모듈 설치 및 메뉴 화면
#### 1) 프로그램 실행
- 1번 메뉴 선택
- 2번 메뉴 선택(상위 20개 데이터 출력)
- 3번 메뉴 선택(축적 데이터 워드 클라우드 시각화)
- 4번 메뉴 선택(축적 데이터 막대 그래프 시각화)
- 5번 메뉴 선택(키워드 브랜드 워드 클라우드 시각화)
- 6번 메뉴 선택(키워드 브랜드 원 그래프 시각화)
- 0번 메뉴 선택(프로그램 종료)
#### 2) 시각화 결과 및 분석
- 인기 검색어 빈도수 데이터 시각화
- 브랜드 빈도수 데이터 시각화
