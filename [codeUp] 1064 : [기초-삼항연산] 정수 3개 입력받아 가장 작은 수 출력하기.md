
---

# [codeUp] 1064 : [기초-삼항연산] 정수 3개 입력받아 가장 작은 수 출력하기 python


## 문제
 
입력된 세 정수 a, b, c 중 가장 작은 값을 출력하는 프로그램을 작성해보자.    
단, 조건문을 사용하지 않고 3항 연산자 ? 를 사용한다.




---
### 입력 

3개의 정수가 공백을 두고 입력된다.
-2147483648 ~ +2147483647


---
### 출력   

가장 작은 값을 출력한다.

---
### 입력 예시

3 -1 5

---
### 출력 예시

-1

---
제출
---
```python
a,b,c=map(int, input().split())
x=a if a<b else b
print (x if x<c else c)
```

---
### 풀이

---
