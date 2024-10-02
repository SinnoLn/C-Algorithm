# 알고리즘 공부

## 그래프 이론

- 그래프가 희소할때는 인접리스트(간선이 많이 없을때), 조밀할때는 인접행렬이 좋음
- 인접행렬  (공간복잡도 O(V+E))
- 인접리스트 (공간복잡도 O(V^2))

**그럼 언제 뭘쓰면 좋을까?**

- 보통은 인접리스트 사용. 문제에서 sparse한 그래프가 많이 나옴
- 다만, 문제 또는 코딩인터뷰에서 인접행렬로 주어진다면 그대로 인접행렬로 푸는게 좋음

인접리스트나 인접행렬을 안쓰고 맵과 방향벡터를 써야하는 경우가 있음

- 지도 기반으로 주어졌을때는 지도 기반으로 풀어야함
- 사람이 상하좌우 한칸 씩 4방향 탐색 (y, x)
