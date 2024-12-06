## 마지막 업데이트
24.12.06

<br>

## 작성자
60191652 문장훈

<br>

## Hypothesis_testing 결과
위에서 작성된 T-test 결과와 Ranksum Test의 결과에서 p-value가 0.05 미만인 데이터를 집계

```python
# 선택된 특성 리스트
selected_features = selected_numeric_features + selected_nominal_features + ["hotel"]
print("=== 선택된 특성 ===")
print(selected_features)
```

```
=== 선택된 특성 ===
['lead_time', 'stays_in_weekend_nights', 'stays_in_week_nights', 'adr', 'total_of_special_requests', 'meal', 'market_segment', 'distribution_channel', 'is_repeated_guest', 'deposit_type', 'customer_type', 'arrival_date_month', 'reserved_room_type', 'hotel']
```

회귀 분석을 진행하기 전에 T-Test와 Ranksum test의 p-value가 0.05 미만이라면, 해당 독립 변수(예: 두 그룹 간 차이)가 통계적으로 유의미하다고 볼 수 있으며, 이를 회귀 모델에 포함시킬 수 있음.

그러나 회귀 모델 자체의 p-value는 회귀 계수가 0이 아닌지, 즉 독립 변수가 종속 변수에 미치는 영향이 유의미한지 평가하는 데 사용되므로, T-test와 Ranksum test의 p-value는 보조적인 역할을 사용.