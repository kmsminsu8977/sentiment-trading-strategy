# 발표 초안

## 1. 문제 정의

단순 감성 신호가 비용을 차감한 뒤에도 방향성 전략으로 의미 있는가?

## 2. 데이터와 가정

- 합성 샘플 데이터: `data/sample/news_signal_returns.csv`
- 재현 가능한 baseline 실행을 우선 구성

## 3. 방법

뉴스 감성 신호를 다음 거래일 포지션으로 연결하고 비용 차감 성과를 계산한다.

## 4. 현재 산출물

- 실행 스크립트: `python -m src.run_baseline`
- 결과 표: `outputs/tables/baseline_results.csv`

## 5. 후속 작업

- 실제 데이터 연결
- 민감도 분석
- 차트/보고서 산출
- 프로젝트별 상세 검증
