# ๐ mobile-reserve

> ๋ชจ๋ฐ์ผ ๊ฒ์ ์ฌ์  ์์ฝ ํ์ด์ง ๊ฐ๋ฐ

## ๐ ์๊ตฌ์ฌํญ

- ์ฟ ํฐ ๋ฒํธ ๋ฐ๊ธ ํ์ด์ง
- ์ฟ ํฐ ์กฐํ ํ์ด์ง

# ๐ Back End

## ๐คผโโ๏ธ ์ฌ์ฉ ๊ธฐ์ 

- Language: Java
- Framework: Spring Boot
- ORM: JPA

## ๐คบ API

- Coupon ์กฐํ API (GET)
- Coupon ๋ฐ๊ธ API (POST)
- Coupon ๋ฆฌ์คํธ ์กฐํ API (GET)

## ๐๏ธโโ๏ธ Coupon Generator Algorithm([์์ค ๋ณด๊ธฐ](https://github.com/minemanemo/mobile-reserve-api/blob/38dcd7e7e2d87ed43e0cbba0ef5c7d7eb92e6964/src/main/java/com/smilegatemegaport/mobilereserveapi/service/CouponServiceHandler.java#L57))

- ์ซ์(0-9), ์๋์๋ฌธ์(a-z, A-Z) ์ด 62(10 + 26 + 26)๊ฐ์ ๋ฌธ์๋ฅผ ๋ฆฌ์คํธ์ ์ ์ฅ
- ๋ฆฌ์คํธ๋ฅผ ์ํํ์ฌ ์์์๋ถํฐ 12์๋ฆฌ๊น์ง ์ฝ์ ๊ฒฐ๊ณผ๋ฅผ ์ฟ ํฐ์ผ๋ก ์ฌ์ฉ
- ์ ๋งํฌ์ generateCouponNumber ํจ์ ์ฐธ์กฐ

# โฝ๏ธ Front End

## โน๏ธโโ๏ธ ์ฌ์ฉ ๊ธฐ์ 

- Language: TypeScript
- Framework: React, React Router, Recoil
- JS in CSS: styled-components, Material UI
- Deploy server: TypsScript & express

# โพ๏ธ Database

- h2 in memory DB ์ฌ์ฉ
