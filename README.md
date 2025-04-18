# 개요

멋쟁이사자처럼 at SCH 9th 제1회 '무쓸모톤' 프로젝트
[무쓸모톤] 세상에서 가장 쓸데없는 서비스를 선보입니다.

---

## 🤴THE-KING 소개

[ 나는 왕이다 : THE-KING ]
생리활동 자랑하기 - 이달의 (대변·소변·방귀)왕

![home 화면](https://user-images.githubusercontent.com/81010175/127639141-bc29acd0-24c3-4d50-8ae3-2050d95f9388.png)

---

## 💻서버 실행방법

1. 프로젝트 clone

- git clone https://github.com/THE-KING-SSAM/THE-KING.git

2. 가상 환경 생성 및 실행

- `. venv/Scripts/activate`

3. 필요한 라이브러리 설치

- `pip install django`
- `pip install pillow`

4. 모델 등록

- `account/models.py history 클래스 주석처리`
- `python manage.py makemigrations account`
- `python manage.py makemigrations board`
- `account/models.py history 클래스 주석처리 취소`
- `python manage.py makemigrations account`
- `python manage.py migrate`

5. 관리자 생성하기

- `python manage.py createsuperuser`

6. 서버 실행

- `python mange.py runserver`

## ✏ Tech Stack

- Django
- Python3
- HTML, CSS

---
