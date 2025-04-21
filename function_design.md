# Function Module 상세 설계 문서 - ZSD_WEB_VA03

## Input Parameters

| 필드명 | 설명 |
|--------|------|
| VDATU  | 납품요청일 |
| KUNNR  | 대리점코드 |
| KUNNR2 | 납품처코드 |
| VKORG  | 회사 코드 |
| VBELN  | 주문번호 |
| POSNR  | 주문라인번호 |

## Output Table: ZSDSWB01

| 필드명 | 설명 |
|--------|------|
| VBELN  | 주문번호 |
| POSNR  | 주문라인 |
| MATNR  | 상품코드 |
| MAKTX  | 상품명 |
| KWMENG | 주문수량 |
| NETPR  | 단가 |
| VRKME  | 단위 |
| NETWR  | 금액 |
| MWSBP  | 부가세 |
| TOAMT  | 합계금액 |
| FLAG   | 출하여부 |
| SEQNO  | 출력순번 |
| NAME1  | 고객명 |
| ZTEXT  | 고객비고 |
| FLAG1  | 납품문서 생성여부 |
| ABGRT  | 거부사유 |
| VBELN2 | 납품문서번호 |
| LFIMG  | 납품수량 |
