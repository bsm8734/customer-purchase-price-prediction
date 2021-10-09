# customer-purchase-price-prediction

정형데이터 분류 소스코드

### 프로젝트 설명
- 온라인 거래 고객 log 데이터를 이용하여 고객들의 미래 소비를 예측 분석
- 5914명의 `2009년 11월 ~ 2011년 11월` 데이터를 이용하여 각 고객들의 `2011년 12월`의 **총 구매액이 300을 넘을지의 확률값을 예측**하는 이진 분류 문제

### 데이터 설명

- 2009년 12월부터 2011년 11월까지의 온라인 상점의 거래 데이터가 주어짐
- 2011년 11월 까지 데이터를 이용하여 2011년 12월의 고객 구매액 300초과 여부를 예측해야 함
- **Unique Customer_id** : 5914명
- **Customer 당 로그 수** : 1개 ~ 12714개

### 데이터 컬럼 설명

- order_id : 주문 번호. 데이터에서 같은 주문번호는 동일 주문을 나타냄
- product_id : 상품 번호
- description : 상품 설명
- quantity : 상품 주문 수량
- order_date : 주문 일자
- price : 상품 가격
- customer_id : 고객 번호
- country : 고객 거주 국가
- total : 총 구매액(quantity X price)

### 평가방식

- AUC(Area Under Curve)

### Feature engineering & Other methods




<br>

> 경진대회 과정에 대한 기록, 사용한 아키텍처는 [Notion](https://shy-perfume-f1a.notion.site/Wrap-Up-2fe14d302e34431da0eed87a051ed013)에 `wrap-up report`로 올려두었습니다.
