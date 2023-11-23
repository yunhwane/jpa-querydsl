# jpa 튜닝 과정 정리 
- 조회 성능 최적화 

## 고급 매핑
1. 지연로딩최적화 v1 엔티티 그대로 노출
- 순환참조문제
- Lazy 문제
- Lazy 문제 해결을 위한 Eager 사용하지 않기
- https://github.com/yunhwane/jpa-querydsl/blob/main/%EC%A7%80%EC%97%B0%EB%A1%9C%EB%94%A9_%EC%A1%B0%ED%9A%8C%EC%84%B1%EB%8A%A5%EC%B5%9C%EC%A0%81%ED%99%94V1.md

2. DTO 변환 후 반환
- N+1 문제 직면 상황
- https://github.com/yunhwane/jpa-querydsl/blob/main/N%2B1%EB%AC%B8%EC%A0%9C.md
