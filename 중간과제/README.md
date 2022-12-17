# 중간과제
### Type Error: data argument cannot be an iterator
- df = pd.DataFrame(data) 부분에서 보통 뜰 건데, data를 list로 감싸주면 오류 해결됨
- ex) df = pd.DataFrame(data) -> df = pd.DataFrame(list(data))


[과제01.pdf](https://github.com/hellojunho/Data_Statistics/files/9763649/01.pdf)
---
### 과제01 문제2번
#### 표준화 데이터란?
- 상대적인 결과가 모두 상이하므로, 통일된 지표로 변환하는 일종의 정규화 과정
- 표준화 데이터(Z) = (데이터(x) - 평균(x')) / 표준편차(S)
