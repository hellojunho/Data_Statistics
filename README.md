# - 데이터통계 과제

###'Type Error: data argument cannot be an iterator'
- df = pd.DataFrame(data) 부분에서 보통 뜰 건데, data를 list로 감싸주면 오류 해결됨
- ex) df = pd.DataFrame(data) -> df = pd.DataFrame(list(data))


[과제01.pdf](https://github.com/hellojunho/Data_Statistics/files/9763649/01.pdf)
