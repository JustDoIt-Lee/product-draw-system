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
- **Build Tool**: Maven

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

## 📝 느낀점 & 회고
- 실무와 유사한 구조로 도메인 설계, JPA 연관관계, 성능 테스트까지 경험하며 백엔드 전반의 흐름을 익힐 수 있었습니다.
- 단순 구현을 넘어 중복 응모 방지 로직 설계와 JMeter 기반 부하 테스트를 통해, 서비스 품질 관점에서 시스템을 바라보는 시야를 키우게 되었습니다.

---

## 📑 기타 문서
- [ERD 보기](./image/ERD.png)
