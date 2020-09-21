
---

# [codeUp] 1066 정수 3개 입력받아 짝홀 출력하기 python


## 문제
 
세 정수 a, b, c가 입력되었을 때, 짝(even)/홀(odd)을 출력해보자.





---
### 입력 

3개의 정수가 공백을 두고 입력된다.
-2147483648 ~ +2147483647


---
### 출력   

입력된 순서대로 짝(even)/홀(odd)을 줄을 바꿔 출력한다.

---
### 입력 예시

1 2 8

---
### 출력 예시

odd
even
even

---
제출
---
```python
a,b,c=map(int, input().split())

def evenOrOdd(x):
    return "even" if x % 2 == 0 else "odd"

print(evenOrOdd(a))
print(evenOrOdd(b))
print(evenOrOdd(c))
```

---
### 풀이
* 함수 첫 등장!
---
