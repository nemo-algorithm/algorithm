### <center>화이트데이<center>

> 메모리 제한: 128 MiB<br>시간제한: 1초

#### 문제

---

어흥 ~ ! 혼자 사는 외로운 호랑이 네모는 안암골의 ALPS 부족에서 귀여운 아기 호랑이들이 태어났다는 소문을 들었다. 네모는 귀여운 아기 호랑이들에게 달달한 페레로 로쉐를 선물해주려고 한다.

ALPS 부족은 n 채의 움막 안에 살고 있다. 각각의 움막에는 1부터 n까지의 번호가 붙어 있다. 한 움막에는 최대 한 마리의 아기호랑이가 태어날 수 있다. 네모는 각 움막의 대표자를 한 명씩 불러 물어보았다. "어느 움막에 아기 호랑이가 태어났니?" 네모가 아기 호랑이를 찾아서 냠냠 잡아먹을까바 겁을 먹은 대표자들은 알쏭달쏭하게 대답하기로 했다.

i번 움막의 대표자는 다음과 같이 대답한다.

> i 로 나눠떨어지는 번호를 가진 움막에서 태어난 호랑이는 $a_{i}$마리 입니다.

귀여운 아기 호랑이들은 대체 몇 번 움막에 살고 있는 걸까? 네모에게 정답을 알려주고 달달한 페레로 로쉐를 받아가자!



#### 입력

----

첫 번째 줄에는 한 개의 정수 $n$이 주어진다.

두번째 줄에는 $a_{i}$에 해당하는 $n$개의 정수가 주어진다.

$1\le n \le 5000$



#### 출력

----

첫 번째 줄에는 아기 호랑이의 개체수를 출력한다.

두 번째 줄에는 아기 호랑이가 사는 움막을 번호 순서대로 출력한다.



#### 예제 입력

---

```
5
3 0 1 0 1
```

#### 예제 출력

---

```
3
1 3 5
```
