# 🎯 Product Draw System

상품 응모(추첨) 시스템 - 고객이 상품을 응모하고, 중복 응모를 방지하는 추첨 기반 백엔드 시스템입니다.

---

## 🔧 개발 환경
- **Language**: Java 17
- **Framework**: Spring Boot
- **DB**: MySQL (dev), Oracle (prod)
- **ORM**: JPA, Hibernate
- **Testing**: JUnit4, JMeter
- **Version Control**: Git
- **Build Tool**: Maven or Gradle (선택한 것 명시)

---

## 🌐 주요 기술 스택
- Lombok, Log4j
- JSP (View), Spring MVC
- Profile 기반 DB 분리 (`dev`, `prod`)
- Git Branch 전략 도입

---

## 📂 기능 요약
- 상품(Product), 고객(Customer), 추첨(Draw) 도메인 설계
- 고객의 중복 응모 방지 로직
- 연관관계 설계 (`@ManyToOne`, `@OneToMany`)
- DTO ↔ Entity 변환
- JPQL과 Native Query 비교 및 최적화

---

## 📈 성능 측정
- Apache JMeter로 TPS, 응답속도 측정
- Thread Group, Loop Count 구성 실험

---

## 📑 기타 문서
- [ERD 보기](https://www.notion.so/ERD-ffffd08c4eee811dbf92cb8851a107bf?pvs=21)
- [스토리보드](https://www.notion.so/ffffd08c4eee8149bb06f4be0678f342?pvs=21)
