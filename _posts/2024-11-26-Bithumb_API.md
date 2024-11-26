---
title: "Bithumb API Price"
excerpt: "Bithumb API를 통한 실시간 가격 표시기"

categories:
    - Blog
tags:
    - [Blog, Python, Bithumb]

toc: true
toc_sticky: true

date: 2024-11-26
last_modified_at: 2024-11-26
---

## Bithumb API Price

개발인원: 1명 / 개발기간: 2024.06.

![lcd.png](assets/posts/lcd.png)

**Bithumb API를 통한 실시간 가격 표시기**

- Python언어로 작성
- Raspberry PI GPIO 핀을 통해 I2C LCD 모듈을 연결하여 I2C통신 라이브러리를 사용해 Bithumb API를 호출한 결과를 표시하도록 구현
- Linux Shell 스크립트를 시스템 Service에 등록하여 따로 실행하지 않더라도 Raspberry Pi 부팅 시 자동으로 시작되도록 해 24시간 작동할 수 있도록 구현
    
    [Github Link](https://github.com/kdj8501/bithumb_api_price)
