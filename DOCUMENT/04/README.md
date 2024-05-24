# IPV4

IPv4 기본
---

> BIT/BYTE <br>

|-|-| 
|-|-| 
|**Bit**|Binary Digit 비트<br>아라비아숫자(0-9)를 2진수(Binary)로 변환 표현할때 표현되는 한자리|  
|Byte(또는 Octet(옥텟)|8bit의 1묶음| 

> > 참고 <br>
```
Nibble(니블)
  - 4bit의 1 묶음
Word(워드)
  - Full Word : 4byte - Half Word : 8byte - Double Word : 8byte
Character(문자)
  - 통상 ASCII 방식으로 1문자를 1byte로 표현
```

IP주소 표현
---

>주소표현방식<br>

|8bit|8bit|8bit|8bit|
|-|-|-|-|
|00000000|00000000|00000000|00000000|

>최대값/최소값<br>

|-|8bit|8bit|8bit|8bit|
|-|-|-|-|-| 
|최소값(2진수)|00000000|00000000|00000000|00000000| 
|최대값(2진수)|11111111|11111111|11111111|11111111| 

> 마디당 10진수 사용범위<br>

|-|-|-|-|-|
|-|-|-|-|-|
|최소값(10진수)|0|0|0|0|
|최대값(10진수)|255|255|255|255|

>미니문제 - > [바로가기](./문제/01.md)<br>

---
#
---

NETWORK IP / HOST IP
---

>NETWORK IP<br>
```
네트워크 영역 식별 IP
```
![20240525003523](https://github.com/MY-ALL-LECTURE/CCNA/assets/84259104/8ad7be96-4272-4192-92f2-4a27d5cf5da2)

>HOST IP<br>
```
호스트간 식별 IP
```
![20240525003529](https://github.com/MY-ALL-LECTURE/CCNA/assets/84259104/7d5dd64a-7b97-4cbb-904d-ed2c3b279216)

