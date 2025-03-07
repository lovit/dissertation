# Ph.D  dissertation Repository

[pdf](dissertation.pdf)

## 미등록단어 문제와 데이터 부족 현상을 해결하기 위한 비지도학습 토크나이저와 추출 기반 문서 요약 기법

### 제 1 장 서론
- 1.1 한국어의 구조 - p.5
- 1.2 단어 임베딩 (Word embedding) - p.6
- 1.3 순차적 레이블링 (Sequential labeling) - p.10
- 1.4 머신 러닝 기반 한국어 품사 판별 - p.17
- 1.5 문서 요약 - p.20
  - 1.5.1 키워드 추출을 이용한 토픽 레이블링 - p.21
  - 1.5.2 그래프 랭킹 기반 키워드와 핵심 문장 추출 - p.23
  - 1.5.3 딥러닝 모델을 이용한 요약 기반 문서 요약 - p.25

### 제 2 장 단어 추출 기법을 이용한 미등록단어 문제 해결 및 이를 이용한 한국어 토크나이저
- 2.1 서론 - p.27
- 2.2 관련 연구 - p.29
- 2.3 비지도기반 한국어 단어 추출 및 이를 이용한 토크나나이저 - p.32
  - 2.3.1 한국어 어절의 구조 : L + [R] - p.32
  - 2.3.2 음절 단위의 언어 모델을 이용한 단어 점수 - p.34
  - 2.3.3 단어 점수를 이용하는 비지도학습 토크나이저 - p.35
- 2.4 성능 평가 - p.38
  - 2.4.1 영화평을 이용한 긍부정 분류 성능 평가 - p.40
  - 2.4.2 메타 데이터를 이용한 고유 명사 재현 능력 평가 - p.41
  - 2.4.3 단어 임베딩을 이용한 유사 단어 검색 성능 평가 - p.42
- 2.5 결론 - p.44

### 제 3 장 한국어 어절 구조를 이용한 통계 기반 명사 추출
- 3.1 서론 - p.46
- 3.2 관련 연구 - p.48
- 3.3 한국어 어절의 L + [R] 구조를 이용한 명사 추출 - p.50
  - 3.3.1 L-R 그래프를 이용한 명사 추출 - p.50
  - 3.3.2 세종 말뭉치를 이용한 명사 판별 분류기 학습 - p.54
- 3.4 성능 평가 - p.57
  - 3.4.1 세종 말뭉치를 이용한 성능 평가 - p.57
  - 3.4.2 뉴스 기사와 온라인 문서를 이용한 성능 평가 - p.59
- 3.5 결론 - p.62

### 제 4 장 단일주제 문서 집합 요약을 위한 그래프 랭킹 기반 키워드와 핵심 문장 추출
- 4.1 서론 - p.68
- 4.2 관련 연구 - p.70
- 4.3 토크나이저를 이용하지 않는 키워드 및 핵심 문장 추출 - p.74
  - 4.3.1 부분어절 그래프와 그래프 랭킹 알고리즘을 이용한 키워드 추출 - p. 74
  - 4.3.2 키워드 집합을 이용한 핵심 문장 선택 - p.76
- 4.4 성능 평가 - p.78
- 4.5 결론 - p.84

### 제 5 장 다주제 문서 집합 요약을 위한 문서 군집화 알고리즘 및 군집 별 키워드 추출
- 5.1 개요 - p.86
- 5.2 관련 연구 - p.87
- 5.3 문서 군집화를 위하여 개선된 Spherical k-means - p.90
  - 5.3.1 효율적인 Spherical k-means 초기화 - p.91
  - 5.3.2 군집 중심값을 이용한 문서 군집 별 키워드 추출 방법 - p.93
- 5.4 성능 평가 - p.94
  - 5.4.1 초기화 방법의 성능 평가 - p.95
  - 5.4.2 문서 군집 별 키워드 추출 방법의 성능 평가 - p.97
- 5.5 중심 벡터의 차원 축소와 군집 레이블을 이용한 군집화 결과 시각화 - p.99
- 5.6 결론 - p.101

### 제 6 장 시계열 형식의 뉴스 문서 집합 요약을 위한 거리 기반 유사 주제 구간 분리
- 6.1 개요 - p.103
- 6.2 관련 연구 - p.104
- 6.3 유사 주제 구간 분리를 이용한 시계열 형식의 문서 요약 - p.108
  - 6.3.1 시계열 분리를 위한 문서 집합의 구간 별 벡터 표현 방법 - p.109
- 6.4 성능 평가 - p.112
  - 6.4.1 질의어 ’김무성’이 포함된 뉴스 기사의 구간 분리 - p.113
  - 6.4.2 질의어 ’박근혜’가 포함된 뉴스 기사의 구간 분리 - p.114
  - 6.4.3 질의어 ’유시민’이 포함된 뉴스 기사의 구간 분리 - p.116
- 6.5 결론 - p.117

### 제 7 장 결론 122
- 7.1 이 논문의 기여 - p.124
- 7.2 후속 연구 - p.126

### 참고문헌

### Abstract

### 감사의 글
