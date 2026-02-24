# 정보 검색

# 🔍 정보 검색 (Information Retrieval) - 2023

이 레포지토리는 2023년 정보 검색(Information Retrieval) 수업 과정 중 수행한 다양한 알고리즘 분석 과제와 Elastic Search를 활용한 기말 프로젝트 결과물을 관리합니다.

## 🛠 주요 프로젝트 및 과제

### 1. 서울시 공공와이파이 지도 시각화 (Term Project)
Elastic Search의 Maps 기능을 활용하여 서울시 내 공공와이파이 설치 현황을 지도상에 구현한 프로젝트입니다.

- **목적**: Elastic Search의 지리 정보 시스템(GIS) 처리 역량을 파악하고 공공 데이터를 시각화함
- **주요 기능**:
    - REST API를 통한 서울시 공공와이파이 데이터(위도, 경도, 주소) 확보
    - Python 클라이언트를 활용한 Elastic Search 데이터 전송 및 사전 인덱스 매핑
    - Kibana Maps를 통한 위치 기반 시각화 구현
- **핵심 기술**: Python, Elastic Search (geo_point mapping), Kibana, REST API

### 2. Porter Stemming 알고리즘 분석 (HW2)
단어의 어근을 추출하는 Porter Stemmer의 원리를 분석하고, 다양한 형태소 분석기(Stemmer)의 결과를 비교하였습니다.

- **분석 내용**:
    - Porter Stemmer의 5단계 알고리즘 및 규칙 분석
    - Stemming의 한계점 및 오류 사례 조사 (예: Wand/Wander, Index/Indices 등)
- **비교 분석**: Porter, Lancaster, Snowball Stemmer를 활용한 테스트 코드 작성 및 결과 비교

### 3. PageRank 알고리즘 분석 (HW3)
웹 페이지의 상대적 중요도를 계산하는 Google의 핵심 알고리즘인 PageRank의 구조를 분석하였습니다.

- **핵심 내용**:
    - 웹 그래프(Web Graph)의 노드와 링크 구조 분석
    - 알고리즘 의사코드(Pseudo Code) 분석을 통한 가중치 수렴 과정 이해

### 4. 검색 엔진 및 소셜 랭킹 알고리즘 (HW4)
- **Elastic Search**: 클러스터, 인덱스, 샤드(Shard)의 개념 및 RDBMS와의 구조적 차이 학습
- **Social Ranking**: 유튜브의 추천 시스템 발전 과정 및 네이버 C-Rank 알고리즘의 특징(출처의 신뢰도 등) 분석

## 💻 개발 환경
- **언어**: Python 3.x (NLTK, Elasticsearch library)
- **엔진**: Elastic Search, Kibana
- **데이터**: 서울시 열린데이터 광장 공공와이파이 API

---
**작성자**: 이진형 (201812167)
