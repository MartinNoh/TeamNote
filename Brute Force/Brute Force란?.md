## 완전 탐색, 브루트 포스란 무엇인가?

> Brute(무식한) + Force(힘)

즉, 발생할 수 있는 모든 경우를 무식하게 탐색한다는 뜻이다.
전체를 탐색한다는 의미에서 전체 탐색, 완전 탐색이라고도 한다.

브루트 포스 알고리즘을 설계할 때는 해가 하나 이상 존재한다는 가정을 세우고 모든 범위를 탐색하기 때문에 무조건 정답을 찾을 수 있다.

#### 장점
- 알고리즘을 설계하고 구현하기 매우 쉽다.
- 복잡한 알고리즘 없이 빠르게 구현할 수 있다.

#### 단점
- 알고리즘의 실행 시간이 매우 오래 걸린다.
- 메모리 효율며에서 매우 비효율적이다.



## 브루트 포스의 종류

브루트 포스는 크게 선형구조와 비선형구조로 나뉜다.
- 선형 구조 : 순차 탐색
- 비선형 구조 : 백트래킹, DFS, BFS