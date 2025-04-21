# ZSD_WEB_VA03 - SAP Sales Document Detail RFC

## 📌 목적
판매 문서 상세 정보를 외부 시스템에 제공하기 위한 RFC Function Module입니다.  
주문번호, 납품요청일자 등으로 조회하여 상품명, 수량, 금액, 납품 상태 등 상세 데이터를 반환합니다.

## 🧠 구성 요소
- Function Module: `ZSD_WEB_VA03`
- Output Structure: `ZSDSWB01`
- 사용 테이블: `VBAK`, `VBAP`, `MAKT`, `KNA1`, 등

## 💡 핵심 특징
- 실무 기반 RFC 명세
- 도메인 필드 + 커스터마이징 필드 활용
- SAP ↔ 외부 연계에 필요한 구조 설계

## 📁 관련 자료
- [명세서 이미지 보기](./docs/zsd_web_va03_spec.png)
- [함수 설계 상세 문서](./function_design.md)
