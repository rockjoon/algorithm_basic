

---

# [codeUp] 1069 : [기초-조건/선택실행구조] 평가 입력받아 다르게 출력하기 python


## 문제
 

평가를 문자(A, B, C, D, ...)로 입력받아 내용을 다르게 출력해보자.

평가 내용   
평가 : 내용   
A : best!!!   
B : good!!   
C : run!    
D : slowly~   
나머지 문자들 : what?점수(정수, 0 ~ 100)를 입력받아 평가를 출력해보자.


---
### 입력 


영문자 1개가 입력된다.   
(A, B, C, D 등의 한 문자가 입력된다.)


---
### 출력   

평가내용에 따라 다른 내용이 출력된다.

---
### 입력 예시

A

---
### 출력 예시

best!!!

---
제출
---
```python
a=input()
def f(x):
    return {
        'A':'best!!!',
        'B':'good!!',
        'C':'run!',
        'D':'slowly~'
    }.get(x, 'what?')
print(f(a))
```

---
### 풀이
* 파이썬에는 switch-case문이 없다. (중대장은 파이썬에 다시 한번 실망했다.)
* 딕셔너리를 이용해 대신 switch-case문 처럼 사용할 수 있다.
* 딕셔너리의 get함소는 첫번째 인자로 key값을, 두번째 인자로 null일 때의 default값을 받는다.
* https://www.pymoon.com/entry/%ED%8C%8C%EC%9D%B4%EC%8D%AC%EC%97%90%EC%84%9C-switchcase%EB%AC%B8-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0
---
