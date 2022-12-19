# 2021 학생 빅데이터 분석 경진대회

### 1. 프로젝트 주제
ESS를 활용한 전기차 충전소 부지 선정

### 2. 분석 방법
 - 연도별 화석연료 사용량 추이
 - 전기차 충전소/충전기 개수 및 전기차 대수 현황
 - 급속/완속 충전소의 시간대별 충전부하량
 - 전국 급속충전기 밀도 현황

### 3. 자료 수집
|사이트|참고자료|주소|
|---|---|---|
|공공 데이터 포털|시간대별 충전부하량|https://www.data.go.kr/index.do|
||산업통상자원부_전국 주유소 등록현황_20141231|
||한국환경공단_전기차 충전기 현황_환경부 공공급속충전기_20200629|
|한국전력공사||https://home.kepco.co.kr/kepco/main.do|
|국토교통부 통계누리|자동차등록현황보고 (Total Registered Moter Vehicles)|https://stat.molit.go.kr/portal/main/portalMain.do|
|한국지역난방공사|한국전력거래소_연간 발전연료사용량추이|https://www.kdhc.co.kr/kdhc/main/main.do|
|저공해차 통합누리|전기차 충전소 모니터링 데이터|https://ev.or.kr/portal/main|
|Github|geodata.json|

### 4. Language & Tool
- Language : Python
- Tool 
  - Module : pandas, folium, json, matplotlib, seaborn 
  - 지도시각화를 위해 카카오맵 API 와 Github에서 행정동 json파일 사용

### 5. 참고한 자료
- 탄소중립관련 정부 보고서 자료 https://www.gihoo.or.kr/netzero/download/LEDS_REPORT.pdf 
- ESS시장 발전 관련 자료
  - https://biz.chosun.com/industry/company/2021/11/15/B5VC6CNYHJHVDBWKTVZJTT7H4Y/
  - http://www.epnc.co.kr/news/articleView.html?idxno=95638
  - https://www.venturesquare.net/784613
  - https://www.youtube.com/watch?v=hdRQxzkEJg0&t
