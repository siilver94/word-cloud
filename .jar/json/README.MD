# JSON (JavaScript Object Notation)

## 📌 JSON이란?
JSON은 **데이터를 구조화하여 저장하고 전송하는 경량 데이터 포맷**입니다.  
텍스트 기반이며, 사람이 읽기 쉽고 기계가 쉽게 처리할 수 있어 API, 설정 파일, 데이터 교환 등에 널리 사용됩니다.

---

## 🔹 JSON 문법
- **키-값 쌍(Key-Value Pair)** 구조로 이루어짐.
- **문자열(String)**은 항상 **큰따옴표("")**로 감싸야 함.
- **데이터 타입**: 문자열, 숫자, 불리언, 배열, 객체, `null` 지원.

```json
{
  "name": "Alice",
  "age": 25,
  "isStudent": false,
  "skills": ["Python", "JavaScript"],
  "address": {
    "city": "Seoul",
    "country": "Korea"
  }
}
