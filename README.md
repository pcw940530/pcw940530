# 안녕하세요, 데이터 직무를 준비하고 있는 박철우입니다 👋

비전공자로 시작해 Python, SQL, 데이터 수집 및 전처리, 데이터베이스 적재와  
클라우드 배포까지 직접 경험하며 데이터 파이프라인의 전체 흐름을 학습하고 있습니다.

단순히 코드를 작성하는 것보다  
**데이터가 어떻게 수집되고, 정리되고, 검증되고, 저장되는지**를 이해하는 데 관심이 많습니다.

웹 애플리케이션 개발부터 데이터 수집·처리, 데이터베이스, 클라우드 환경까지  
직접 구현해보며 데이터가 서비스에서 활용되는 전체 흐름에 대한 이해를 넓혀가고 있습니다.

---

## 💡 About Me

- 데이터 엔지니어링 / 데이터 분석 직무를 준비하고 있습니다.
- Python과 SQL을 중심으로 데이터 처리 역량을 학습하고 있습니다.
- Selenium을 활용한 동적 웹 크롤링 경험이 있습니다.
- Pandas를 활용한 데이터 전처리 및 품질 검증 경험이 있습니다.
- MySQL을 활용한 데이터 적재 및 중복 데이터 관리 경험이 있습니다.
- Spring Boot 기반 웹 애플리케이션 개발 경험이 있습니다.
- GitHub Actions를 이용한 CI 환경을 구성해본 경험이 있습니다.
- AWS SAM / CloudFormation / Lambda를 활용한 배포 및 실행 검증 경험이 있습니다.

---

## 🛠 Tech Stack

### Language
- Python
- Java
- SQL
- JavaScript

### Data
- Pandas
- Selenium
- MySQL

### Backend / Web
- Spring
- Spring Boot
- HTML / CSS / JavaScript

### DevOps / Cloud
- Git
- GitHub
- GitHub Actions
- AWS
- AWS SAM
- AWS Lambda
- CloudFormation

---

# 📌 Projects

## 👟 01. Shoe Data Pipeline

### 신발 상품 데이터 수집부터 DB 적재까지 구현한 개인 데이터 파이프라인 프로젝트

신발 편집샵의 상품 데이터를 Selenium으로 동적으로 수집하고,  
Pandas를 이용한 전처리와 데이터 품질 검증을 거쳐 MySQL에 적재하는 파이프라인을 구현했습니다.

단순 크롤링에서 끝내지 않고 데이터가 수집된 이후  
**Raw 저장 → 전처리 → 품질 검증 → DB 적재**까지 하나의 흐름으로 구성하는 것을 목표로 진행했습니다.

프로젝트 후반에는 GitHub Actions를 이용한 CI 환경을 구성하고,  
AWS SAM / CloudFormation을 활용하여 Lambda 배포 및 실제 실행까지 검증했습니다.

### 🔄 Pipeline

`Dynamic Crawling` → `Raw Data` → `Transform` → `Quality Gate` → `MySQL`

### 🔧 주요 구현

- Selenium 기반 동적 웹 크롤링
- 브랜드별 상품 데이터 수집
- Raw / Staging 데이터 분리
- Pandas 기반 가격 데이터 전처리
- 데이터 품질 검증(Quality Gate)
- MySQL 데이터 적재
- URL 기준 중복 데이터 Upsert
- `main.py` 기반 전체 파이프라인 통합
- GitHub Actions 기반 CI
- AWS SAM / CloudFormation 기반 Lambda 배포 및 실행 검증

### 🛠 Tech

`Python` `Selenium` `Pandas` `MySQL` `GitHub Actions` `AWS` `SAM` `Lambda` `CloudFormation`

### 🔗 Project Repository

[👉 Shoe Data Pipeline 프로젝트 자세히 보기](https://github.com/pcw940530/soldout-data-pipeline)

---

## 👟 02. SENCE:신

### Spring Boot 기반 신발 셀렉트샵 웹 프로젝트

다양한 신발 브랜드와 상품을 탐색할 수 있는  
**신발 셀렉트샵 웹 애플리케이션**을 제작했습니다.

HTML / CSS / JavaScript를 활용하여 사용자 화면을 구성하고,  
Spring Boot 기반으로 Controller와 DTO를 구성하면서  
Frontend와 Backend가 연결되는 웹 애플리케이션의 기본 구조를 학습했습니다.

또한 MySQL 연결 환경을 구성하면서  
웹 애플리케이션과 데이터베이스가 연결되는 흐름을 경험했습니다.

### 🖥 주요 화면

`Main` → `Brand` → `Product Detail` → `Cart`

회원 관련 화면으로 회원가입, 로그인, 마이페이지를 구성했습니다.

### 🔧 주요 구현

- Spring Boot 기반 웹 프로젝트 구성
- Controller / DTO 구조 구현
- HTML / CSS / JavaScript 기반 사용자 화면 구현
- 브랜드별 상품 페이지 구성
- 상품 상세 페이지 구현
- 장바구니 화면 구성
- 회원가입 / 로그인 / 마이페이지 화면 구성
- MySQL 연동 환경 구성
- 페이지 간 이동 및 사용자 흐름 구현

### 🛠 Tech

`Java` `Spring Boot` `HTML5` `CSS3` `JavaScript` `MySQL` `Gradle`

### 🔗 Project Repository

[👉 SENCE:신 프로젝트 자세히 보기](https://github.com/pcw940530/spring-sence)

---

## 📚 Currently Learning

- SQL 데이터 분석
- Python 데이터 처리
- 데이터 파이프라인 설계
- AWS 기반 데이터 / 클라우드 환경
- Git / GitHub 협업 및 자동화

---

## 🎯 Goal

데이터를 단순히 수집하는 것에서 끝내지 않고,  
**신뢰할 수 있는 데이터가 실제 서비스와 의사결정에 활용될 수 있도록 만드는 사람**으로 성장하는 것이 목표입니다.

웹 서비스와 데이터 처리 과정을 함께 이해하는 경험을 바탕으로,  
데이터의 수집부터 저장과 활용까지 전체 흐름을 이해할 수 있는 데이터 직무 인재로 성장하고자 합니다.

---

## 📫 Contact

- GitHub: @pcw940530
