# Australia 부동산 데이터셋 샘플

<h2>1,000개 레코드의 샘플 데이터셋</h2>

<a href="https://brightdata.co.kr">
    <img src="https://github.com/bright-kr/BrightData-Australia-Real-Estate-dataset-samples/blob/main/datasets-image.png" alt="Bright Data datasets" />
</a>

이 **Australia 부동산 데이터셋 샘플**에는 **1,000개 레코드**가 포함되어 있으며, **Bright Data API**를 사용해 추출되었습니다.

## 데이터 포인트

| 필드 이름 | 설명 |
|------------|-------------|
| `rea_property_id` | 부동산 매물의 고유 식별자입니다. |
| `property_type` | House, Unit, Apartment와 같은 부동산 유형입니다. |
| `state` | 해당 부동산이 위치한 호주의 주(state)입니다. |
| `postcode` | 부동산 위치의 우편번호입니다. |
| `year_built` | 부동산이 건축된 연도입니다. |
| `last_sold_date` | 부동산이 마지막으로 판매된 날짜입니다. |
| `last_sold_agency` | 해당 부동산을 마지막으로 판매한 부동산 중개업체입니다. |
| `bedrooms` | 부동산의 침실 수입니다. |
| `bathrooms` | 부동산의 욕실 수입니다. |
| `findAgentsURI` | 해당 부동산 매물과 관련된 에이전트를 찾을 수 있는 URL입니다. |
| `floor_area` | 부동산의 총 바닥 면적입니다. |
| `fullSuburb` | 해당 부동산이 위치한 suburb의 전체 이름입니다. |
| `house_type` | 구조적 특성을 나타내는 구체적인 주택 유형입니다. |
| `lat` | 부동산 위치의 위도 좌표입니다. |
| `lon` | 부동산 위치의 경도 좌표입니다. |
| `photo_count` | 해당 부동산 매물에 제공되는 사진 수입니다. |
| `images_urls` | 해당 부동산 매물과 연결된 이미지 URL입니다. |
| `street_address` | 부동산의 도로명 주소입니다. |
| `suburb` | 해당 부동산이 위치한 suburb입니다. |
| `url` | 부동산 온라인 매물 페이지의 URL입니다. |
| `land_size` | 해당 부동산이 위치한 토지의 크기입니다. |
| `sales_history` | 부동산의 과거 판매 데이터입니다. |
| `land_size_num` | 토지 크기의 수치 값입니다. |
| `land_size_unit` | 토지 크기에 대한 측정 단위입니다. |
| `floor_area_num` | 바닥 면적의 수치 값입니다. |
| `avm_estimate_lastUpdated` | 자동 가치 평가 모델이 마지막으로 업데이트된 날짜입니다. |
| `estimated_price` | 부동산의 추정 시장 가격입니다. |
| `estimated_price_confidence` | 추정 가격 값에 대한 신뢰 수준입니다. |
| `estimated_value` | 다양한 요소를 기반으로 계산된 부동산 가치입니다. |
| `estimated_value_high` | 추정 부동산 가치의 상한 범위입니다. |
| `estimated_value_low` | 추정 부동산 가치의 하한 범위입니다. |
| `offMarket` | 해당 부동산이 현재 시장에 나와 있지 않은지 여부를 나타냅니다. |
| `parking` | 부동산의 주차 가능 여부에 대한 세부 정보입니다. |
| `listing_type` | sale 또는 rent와 같은 매물 유형입니다. |
| `availability` | 부동산의 현재 이용 가능 상태입니다. |
| `rent_price` | 해당 부동산이 임대 가능한 가격입니다. |
| `rent_currency` | 임대료가 표시되는 통화입니다. |
| `rent_bond` | 부동산 임대를 위해 필요한 보증금 금액입니다. |
| `sold_date` | 부동산이 공식적으로 판매된 날짜입니다. |
| `property_history_link` | 부동산의 과거 데이터로 연결되는 링크입니다. |
| `description` | 부동산 매물에 대한 상세 설명입니다. |
| `agents` | 해당 부동산 매물을 관리하는 에이전트 정보입니다. |
| `branding` | 해당 부동산 매물과 관련된 브랜딩 정보입니다. |
| `listed_at` | 부동산이 시장에 등록된 날짜입니다. |


## 활용 사례

### 1. 시장 트렌드 분석
이 데이터셋을 활용하여 호주 부동산 시장의 트렌드를 식별하고 예측함으로써 투자 전략 수립과 정책 결정에 도움을 줄 수 있습니다.

### 2. 부동산 가치 평가 모델
다양한 요소를 기반으로 부동산 가치를 예측하는 머신러닝 모델을 개발하여 부동산 전문가의 평가 정확도를 높일 수 있습니다.

### 3. 경쟁 구도 평가
중개업체 판매 데이터를 분석하여 경쟁사의 활동과 전략을 파악하고, 부동산 비즈니스가 시장 내 포지셔닝을 개선할 수 있도록 지원합니다.



## 파일 형식

이 데이터셋은 여러 형식으로 제공됩니다:
- **CSV** (이 샘플에 포함됨)
- **JSON**
- **NDJSON**
- **JSON Lines**
- **Parquet**
- **Compressed (.gz)**

## 제공 옵션

- **Email**
- **API Download**
- **Webhook**
- **Amazon S3**
- **Google Cloud Storage**
- **Microsoft Azure**
- **Snowflake**
- **SFTP**

## 업데이트 주기

데이터셋은 다양한 일정으로 업데이트될 수 있습니다:
- **Once** (일회성 제공)
- **Daily**
- **Weekly**
- **Monthly**
- **Quarterly**
- **Custom schedules**

## 데이터 보강

특정 요구사항에 따라 추가 데이터 포인트로 데이터셋을 강화할 수 있습니다. 맞춤형 enrichment 옵션에 대해서는 문의해 주세요.

**[전체 Australia 부동산 데이터셋 받기](https://brightdata.co.kr/products/datasets/real-estate)**

---

## 연구자 및 NGO를 위한 무료 액세스

Bright Initiative는 환경 및 사회적 이슈를 다루는 학술 연구자, NGO, NPO를 위해 **[Web Scraper APIs](https://brightdata.co.kr/products/web-scraper)** 및 **[바로 사용할 수 있는 데이터셋](https://brightdata.co.kr/products/datasets)**에 대한 무료 액세스를 제공합니다. 

무료 액세스는 [brightinitiative.com](https://brightinitiative.com)에서 신청하세요.