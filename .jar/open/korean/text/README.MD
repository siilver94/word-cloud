# Open Korean Text - 한국어 형태소 분석기  

## 📌 Open Korean Text란?  
**Open Korean Text**는 한국어 자연어 처리를 위한 **오픈소스 형태소 분석기**입니다.  
원래 **트위터(Twitter)**에서 개발되었으나, 이후 **오픈소스 프로젝트**로 독립하여 발전하였습니다.  

주요 기능으로 **텍스트 정규화, 형태소 분석, 한국어 토큰화** 등을 지원하며,  
특히 **Java 및 Scala 기반 프로젝트에서 한국어 처리가 필요할 때 유용하게 사용**됩니다.  

---

## 🔹 주요 특징  
✔ **한국어 텍스트 정규화**: 맞춤법 오류 및 비표준 표현을 정리.  
✔ **형태소 분석**: 단어를 형태소 단위로 분리하여 문법적 의미를 분석.  
✔ **토큰화(Tokenization)**: 문장에서 유의미한 단어를 추출하여 분석 가능.  
✔ **Java & Scala 지원**: Java 및 Scala 기반의 프로젝트에서 손쉽게 사용 가능.  
✔ **Spring Boot / Gradle 환경과 호환**: Spring Boot 및 Gradle 기반 서비스에서 활용 가능.  

---

## 🔹 설치 방법  
### 1️⃣ Maven 프로젝트  
```xml
<dependency>
    <groupId>org.openkoreantext</groupId>
    <artifactId>open-korean-text</artifactId>
    <version>2.1.0</version>
</dependency>
