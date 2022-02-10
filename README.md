# 가맹점용 관리어플 - REST API 서버와 연동

|순번|요구사항내용|반영계획|반영일자|
|--|------|------|------|
|1|MainActivity Navigation Bar 구성|2022.02.15|~|
|2|MainActivity Home Grid DashBoard 구성|2022.02.15|~|
|3|SubActivity Detail 페이지 구성|2022.02.15|~|
|99|REST API json 규격 정의 회의|2022.02.15|~|

## 상세 (2022-02-10 수정)

프랜차이즈 가맹점주용 관리어플리케이션. 

여러 가맹점주 전용 어플리케이션을 참조하여 기능구성

참조 어플리케이션 : 캐시노트

기본적인 기능
- 내 가게 재무현황 (카드매출 입금 및 결제, 세금계산서)
- 매출추이 (기간별 매출추이, 재방문고객 분석 등)
- 미지급진단
- 내 가게 입소문 모니터링 리뷰관리
- 내 가게 고객 분석, 방문 분석 (내 손님들의 방문빈도, 방문주기 등 방문행태)


## 환경

- Android Studio
- Java 11
- AWS 서버 기반

## 적용 예정 기술

1. Room Database
2. Navigation Bar Activity
3. Chart Library (회의 후 적용 lib 선정)
4. Android BioAuthentication 

## Related Repository

https://github.com/sunwook1996/spring-jpa-with-h2

이 프로젝트는 위 프로젝트 REST API를 받아서 동작합니다.
