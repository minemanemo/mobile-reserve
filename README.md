# 😁 mobile-reserve

> 모바일 게임 사전 예약 페이지 개발

## 😁 요구사항

- 쿠폰 번호 발급 페이지
- 쿠폰 조회 페이지

# 🏀 Back End

## 🤼‍♂️ 사용 기술

- Language: Java
- Framework: Spring Boot
- ORM: JPA

## 🤺 API

- Coupon 조회 API (GET)
- Coupon 발급 API (POST)
- Coupon 리스트 조회 API (GET)

## 🏌️‍♀️ Coupon Generator Algorithm([소스 보기](./mobile-reserve-api/src/main/java/com/smilegatemegaport/mobilereserveapi/service/CouponServiceHandler.java))

- 숫자(0-9), 영대소문자(a-z, A-Z) 총 62(10 + 26 + 26)개의 문자를 리스트에 저장
- 리스트를 셔플하여 앞에서부터 12자리까지 읽은 결과를 쿠폰으로 사용
- 위 링크의 generateCouponNumber 함수 참조

# ⚽️ Front End

## ⛹️‍♀️ 사용 기술

- Language: TypeScript
- Framework: React, React Router, Recoil
- JS in CSS: styled-components, Material UI
- Deploy server: TypsScript & express

# ⚾️ Database

- h2 in memory DB 사용
