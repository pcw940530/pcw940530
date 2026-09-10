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

<table>
<tr>
<td width="50%" valign="top">

### 01. Shoe Data Pipeline

**신발 상품 데이터 수집부터 DB 적재 및  
클라우드 배포까지 구현한 데이터 파이프라인**

<br>

Selenium으로 신발 상품 데이터를 동적으로 수집하고,  
Pandas를 통한 전처리와 품질 검증을 거쳐 MySQL에 적재했습니다.

단순 크롤링에서 끝내지 않고 데이터 수집 이후의 처리 과정을  
하나의 파이프라인으로 연결하는 것을 목표로 진행했습니다.

<br>

**Data Flow**

`Crawling` → `Raw` → `Transform`  
→ `Quality Gate` → `MySQL`

<br>

**Tech**

`Python` `Selenium` `Pandas`  
`MySQL` `GitHub Actions` `AWS`

<br>

<a href="https://github.com/pcw940530/soldout-data-pipeline">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white">
</a>

</td>

<td width="50%" valign="top">

### 02. SENCE:신

**Spring Boot 기반  
신발 셀렉트샵 웹 애플리케이션**

<br>

다양한 신발 브랜드와 상품을 탐색할 수 있는  
신발 셀렉트샵 웹 애플리케이션을 제작했습니다.

HTML / CSS / JavaScript로 사용자 화면을 구현하고  
Spring Boot의 Controller와 DTO 구조를 적용하면서  
웹 애플리케이션의 기본 구조를 경험했습니다.

<br>

**Service Flow**

`Main` → `Brand`  
→ `Product Detail` → `Cart`

<br>

**Tech**

`Java` `Spring Boot` `MySQL`  
`HTML5` `CSS3` `JavaScript`

<br>

<a href="https://github.com/pcw940530/spring-sence">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white">
</a>

</td>
</tr>
</table>

<br>

### Project Details

<details>
<summary><strong>01. Shoe Data Pipeline — 주요 구현 내용</strong></summary>

<br>

- Selenium 기반 동적 웹 크롤링
- 브랜드별 상품 데이터 수집
- Raw / Staging 데이터 분리
- Pandas 기반 가격 데이터 전처리
- 데이터 품질 검증 (Quality Gate)
- MySQL 데이터 적재
- URL 기준 중복 데이터 Upsert
- `main.py` 기반 전체 파이프라인 통합
- GitHub Actions 기반 CI
- AWS SAM / CloudFormation 기반 Lambda 배포 및 실행 검증

<br>

**Pipeline**

```text
Dynamic Crawling
       │
       ▼
    Raw Data
       │
       ▼
   Transform
       │
       ▼
 Quality Gate
       │
       ▼
     MySQL
```

</details>

<details>
<summary><strong>02. SENCE:신 — 주요 구현 내용</strong></summary>

<br>

- Spring Boot 기반 프로젝트 구성
- Controller / DTO 구조 구현
- HTML / CSS / JavaScript 기반 사용자 화면 구현
- 브랜드별 상품 페이지 구성
- 상품 상세 페이지 구현
- 장바구니 화면 구성
- 회원가입 / 로그인 / 마이페이지 화면 구성
- MySQL 연동 환경 구성
- 페이지 간 사용자 이동 흐름 구현

<br>

**Service Flow**

```text
Main
 │
 ▼
Brand
 │
 ▼
Product Detail
 │
 ▼
Cart

Sign Up · Login · My Page
```

</details>

<br>

---

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
