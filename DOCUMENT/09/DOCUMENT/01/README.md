# IGP

---
# DISTANCE VECTOR
---

RIP
---
|-|
|-|
|[참고](https://haekt-log.tistory.com/68)|

> RIP
```
Distance Vector Routing Protocol (거리와 방향을 보고 라우팅을 한다.)
Metric : Hop Count (라우터 개수), 15대까지
소규모 네트워크에 사용
Multicast Address : 224.0.0.9 (D Class)
정보 교환(광고)을 30초마다
수렴 시간 늦다.

- 동작 방식.
1> Update Packet 교환(30초마다)
2> RIP Database에 업데이트 정보 저장
# show ip rip database
3> Routing Tab
le Update
# show ip route
- 명령어
[R1]
router rip
version 2
network 1.0.0.0
network 192.168.10.0
no auto-summary

[R2]
router rip
version 2 
network 1.0.0.0
network 192.168.20.0
no auto-summary

```

