<div align="center">

# 안녕하세요, 데이터 속 이야기를 찾아가는 박철우입니다.

Python과 SQL을 중심으로 데이터 수집·전처리·분석을 공부하며,  
**숫자와 데이터 속에 담긴 의미를 이해하는 과정**에 관심을 가지고 있습니다.

웹 개발부터 데이터베이스, 클라우드까지 직접 구현하며  
데이터와 서비스가 연결되는 전체 흐름에 대한 경험을 넓혀가고 있습니다.

</div>

<br>

---

## About Me

> **데이터가 어떻게 만들어지고, 흘러가고, 활용되는지를 이해하고 싶습니다.**

비전공자로 시작해 현재 **데이터 엔지니어링 / 데이터 분석 직무**를 준비하고 있습니다.

하나의 기술을 배우는 것보다 직접 프로젝트를 만들어보면서  
**수집 → 전처리 → 검증 → 저장 → 활용**으로 이어지는 데이터의 전체 흐름을 경험하고 있습니다.

<table>
<tr>
<td><strong>Data Collection</strong></td>
<td>Selenium을 활용한 동적 웹 데이터 수집</td>
</tr>
<tr>
<td><strong>Data Processing</strong></td>
<td>Pandas 기반 데이터 전처리 및 품질 검증</td>
</tr>
<tr>
<td><strong>Database</strong></td>
<td>MySQL 데이터 적재 및 중복 데이터 관리</td>
</tr>
<tr>
<td><strong>Backend</strong></td>
<td>Spring Boot 기반 웹 애플리케이션 개발</td>
</tr>
<tr>
<td><strong>CI</strong></td>
<td>GitHub Actions 기반 CI 환경 구성</td>
</tr>
<tr>
<td><strong>Cloud</strong></td>
<td>AWS SAM · CloudFormation · Lambda 배포 및 실행 검증</td>
</tr>
</table>

<br>

---

## Tech Stack

<table>
<tr>
<td width="150"><strong>Language</strong></td>
<td>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">

</td>
</tr>

<tr>
<td><strong>Data</strong></td>
<td>

<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">

</td>
</tr>

<tr>
<td><strong>Backend / Web</strong></td>
<td>

<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">

</td>
</tr>

<tr>
<td><strong>DevOps / Cloud</strong></td>
<td>

<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20SAM-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white">
<img src="https://img.shields.io/badge/CloudFormation-759C3E?style=flat-square&logo=amazonwebservices&logoColor=white">

</td>
</tr>
</table>

<br>

---

# Projects

## 01. Shoe Data Pipeline

> **신발 상품 데이터 수집부터 전처리, 품질 검증, DB 적재 및 클라우드 배포까지 구현한 데이터 파이프라인**

<table>
<tr>
<td><strong>프로젝트 형태</strong></td>
<td>개인 프로젝트 · 1인 개발</td>
</tr>
<tr>
<td><strong>주요 역할</strong></td>
<td>데이터 수집 · 전처리 · 품질 검증 · DB 적재 · CI · AWS 배포</td>
</tr>
<tr>
<td><strong>Tech</strong></td>
<td>Python · Selenium · Pandas · MySQL · GitHub Actions · AWS</td>
</tr>
</table>

### Overview

신발 편집샵의 상품 데이터를 활용하여  
**데이터 수집부터 저장까지 이어지는 전체 파이프라인을 직접 설계하고 구현한 개인 프로젝트**입니다.

Selenium을 이용하여 동적으로 상품 데이터를 수집하고,  
수집한 Raw Data를 Pandas로 전처리한 뒤 데이터 품질 검증 과정을 거쳐 MySQL에 적재했습니다.

단순히 크롤링 결과를 파일로 저장하는 것에서 끝내지 않고,

**수집 → 원본 보존 → 전처리 → 품질 검증 → DB 적재**

과정을 하나의 실행 흐름으로 연결하는 것을 목표로 진행했습니다.

프로젝트 후반에는 GitHub Actions를 이용하여 CI 환경을 구성하고,  
AWS SAM / CloudFormation을 활용하여 Lambda 배포와 실제 실행까지 검증했습니다.

### Data Pipeline

```text
┌─────────────────────┐
│   Dynamic Crawling  │
│      Selenium       │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│      Raw Data       │
│   원본 데이터 보존   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│      Transform      │
│       Pandas        │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│    Quality Gate     │
│   데이터 품질 검증   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│       MySQL         │
│    데이터 최종 적재  │
└─────────────────────┘
```

### Key Features

| 영역 | 구현 내용 |
|---|---|
| **Data Collection** | Selenium 기반 동적 웹 크롤링 및 브랜드별 상품 데이터 수집 |
| **Raw Data** | 수집 데이터의 원본 보존 및 Raw / Staging 데이터 분리 |
| **Processing** | Pandas 기반 가격 및 상품 데이터 전처리 |
| **Quality** | 적재 전 데이터 품질 검증을 위한 Quality Gate 구성 |
| **Database** | MySQL 데이터 적재 및 URL 기준 중복 데이터 Upsert |
| **Pipeline** | `main.py`를 중심으로 수집 → 처리 → 검증 → 적재 과정 통합 |
| **CI** | GitHub Actions를 활용한 CI 환경 구성 |
| **Cloud** | AWS SAM / CloudFormation 기반 Lambda 배포 및 실행 검증 |

### What I Learned

이 프로젝트를 통해 단순히 데이터를 가져오는 크롤링 작업과  
**데이터를 지속적으로 사용할 수 있도록 관리하는 파이프라인의 차이**를 경험했습니다.

특히 수집된 데이터를 바로 사용하는 것이 아니라  
Raw 데이터를 보존하고, 전처리와 품질 검증 단계를 거친 뒤 DB에 적재하면서  
데이터의 **정확성, 재사용성, 중복 관리**를 함께 고려하는 경험을 할 수 있었습니다.

또한 로컬 환경에서 동작하는 코드를 GitHub Actions와 AWS 환경으로 확장하면서  
코드 작성 이후의 **배포와 실행 환경**까지 경험했습니다.

### Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-759C3E?style=flat-square&logo=amazonwebservices&logoColor=white)

<br>

<a href="https://github.com/pcw940530/soldout-data-pipeline">
<img src="https://img.shields.io/badge/Repository-Shoe%20Data%20Pipeline-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

<br><br>

---

<br>

## 02. SENCE:신

> **브랜드별 신발을 탐색할 수 있도록 제작한 Spring Boot 기반 신발 셀렉트샵 웹 프로젝트**

<table>
<tr>
<td><strong>프로젝트 형태</strong></td>
<td>개인 프로젝트 · 1인 개발</td>
</tr>
<tr>
<td><strong>주요 역할</strong></td>
<td>기획 · UI 구현 · Backend 구조 구성 · DB 연동</td>
</tr>
<tr>
<td><strong>Tech</strong></td>
<td>Java · Spring Boot · HTML5 · CSS3 · JavaScript · MySQL · Gradle</td>
</tr>
</table>

### Overview

다양한 신발 브랜드와 상품을 하나의 공간에서 탐색할 수 있도록 제작한  
**Spring Boot 기반 신발 셀렉트샵 웹 애플리케이션**입니다.

브랜드가 가진 이미지와 분위기를 웹 화면에서 표현하는 것을 목표로  
메인 페이지부터 브랜드별 페이지, 상품 상세, 장바구니, 회원 관련 화면까지 직접 구성했습니다.

HTML / CSS / JavaScript를 이용한 화면 제작에서 끝내지 않고  
Spring Boot의 Controller와 DTO 구조를 적용하고 MySQL 연결 환경을 구성하면서

**Frontend → Backend → Database**

로 이어지는 웹 애플리케이션의 기본적인 구조를 학습했습니다.

### Service Structure

```text
                    ┌──────────────┐
                    │     Main     │
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │    Brand     │
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │Product Detail│
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │     Cart     │
                    └──────────────┘

               Sign Up · Login · My Page
```

### Key Features

| 영역 | 구현 내용 |
|---|---|
| **Main** | 셀렉트샵 메인 화면 및 브랜드·상품 탐색 UI 구성 |
| **Brand** | 브랜드별 독립 페이지 및 상품 정보 화면 구성 |
| **Product** | 상품 상세 페이지 및 페이지 이동 흐름 구현 |
| **Cart** | 장바구니 사용자 화면 구성 |
| **Member** | 회원가입 · 로그인 · 마이페이지 화면 구성 |
| **Frontend** | HTML / CSS / JavaScript 기반 UI 및 사용자 인터랙션 구현 |
| **Backend** | Spring Boot Controller / DTO 구조 구성 |
| **Database** | MySQL 연결 환경 구성 |

### Project Structure

```text
spring-sence
│
├── controller
│   ├── MemberController
│   └── ProductController
│
├── dto
│   ├── Member
│   └── ProductDto
│
├── static
│   ├── Main
│   ├── Brand
│   ├── Product Detail
│   ├── Cart
│   ├── My Page
│   └── Sign Up
│
├── templates
│   └── Login
│
└── MySQL
```

### What I Learned

SENCE:신 프로젝트를 통해 하나의 화면만 구현하는 것이 아니라  
여러 페이지가 연결된 **웹 서비스의 전체 사용자 흐름**을 직접 구성해볼 수 있었습니다.

또한 Frontend와 Backend를 각각 별개의 기술로 보는 것이 아니라  
사용자의 요청이 Controller를 거쳐 처리되고 데이터와 연결되는 구조를 경험하면서  
웹 애플리케이션이 동작하는 기본적인 흐름을 이해할 수 있었습니다.

이 경험은 이후 데이터 프로젝트를 진행하면서도  
**데이터가 실제 애플리케이션과 서비스에서 어떻게 사용될 수 있는지** 이해하는 기반이 되었습니다.

### Tech Stack

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

<br>

<a href="https://github.com/pcw940530/spring-sence">
<img src="https://img.shields.io/badge/Repository-SENCE%3A신-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

<br>
## Currently Learning

<table>
<tr>
<td width="25%" align="center"><strong>SQL</strong></td>
<td width="25%" align="center"><strong>Python</strong></td>
<td width="25%" align="center"><strong>Data Pipeline</strong></td>
<td width="25%" align="center"><strong>AWS</strong></td>
</tr>

<tr>
<td align="center">
조회 · 집계<br>
JOIN · Subquery
</td>

<td align="center">
데이터 처리<br>
전처리
</td>

<td align="center">
수집 · 검증<br>
적재
</td>

<td align="center">
Cloud<br>
Data Environment
</td>
</tr>
</table>

<br>

---

## Where I'm Going

데이터를 안정적으로 수집하고 관리하는 것에서 멈추지 않고,  
그 데이터를 통해 **왜 이런 현상이 발생했는지 이해하는 것**에 관심이 있습니다.

결과를 다양한 관점에서 바라보고 다른 사람들과 의견을 나누며,  
제가 미처 발견하지 못했던 새로운 인사이트를 찾아가는 과정도 중요하게 생각합니다.

궁극적으로는 데이터를 단순히 처리하는 것을 넘어,

> **데이터를 근거로 현상을 설명하고,  
> 다음에 무엇을 해볼 수 있을지 제안할 수 있는 사람**

으로 성장하는 것이 목표입니다.

<br>

---

<div align="center">

### Contact

<a href="https://github.com/pcw940530">
<img src="https://img.shields.io/badge/GitHub-pcw940530-181717?style=flat-square&logo=github&logoColor=white">
</a>

<br><br>

<sub>꾸준히 배우고, 직접 구현하며 경험을 쌓아가고 있습니다.</sub>

</div>
