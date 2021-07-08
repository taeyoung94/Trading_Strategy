# Trading_Strategy

## 1. Pulling out better stocks from kospi

1) ✍ Summary
- **활용DB**: 주가, 재무제표 from yahoo-finance
- **분석목표**: 다양한 방법으로 최적의 주식 추천
- **성과**: Fundamental 분석, 기술적 분석, 클러스터링, 백테스팅, 미래예측

2) 접근방향
> - 펀더멘탈 분석에 필요한 ratios 선택
> - 투자자 측면에서 선호하는 집단 클러스터링에서 선택
> - 기술적 분석과 백 테스팅을 통해 상반기 수익률 분석
> - 하반기 수익 예측

3) 모델링 기준
>     1) 횡적 리스크 모델링 (BL 사용)
>     2) 종적 리스크 모델링 (주식 종목들만 사용)
>     3) Deep-learning과 Backtesting 활용하여 예측 및 최소 Drawdown 값 도출
