
---

# [codeUp] 1056 참 거짓이 서로 다를 때에만 참 출력하기 파이썬


## 문제

두 개의 참(1) 또는 거짓(0)이 입력될 때,
참/거짓이 서로 다를 때에만 참을 출력하는 프로그램을 작성해보자.




---
### 입력 

1 또는 0의 값만 가지는 2개의 정수가 공백을 두고 입력된다.



---
### 출력   

참/거짓이 서로 다를 때에만 1을 출력하고, 그 외의 경우에는 0을 출력한다.


---
### 입력 예시

1 1

---
### 출력 예시

0

---
제출
---
```python
a,b=input().split()
z=not(a == b)
print(int(z))
```

---
### 풀이
* 

---
