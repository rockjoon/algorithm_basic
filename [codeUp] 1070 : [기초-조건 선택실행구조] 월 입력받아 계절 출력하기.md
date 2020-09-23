
---

# [codeUp] 1070 : [기초-조건 선택실행구조] 월 입력받아 계절 출력하기 python


## 문제
 

월이 입력될 때 계절 이름이 출력되도록 해보자.

월 : 계절 이름   
12, 1, 2 : winter   
  3, 4, 5 : spring   
  6, 7, 8 : summer   
  9, 10, 11 : fall   

---
### 입력 

월을 의미하는 1개의 정수가 입력된다.(1 ~ 12)


---
### 출력   

계절 이름을 출력한다.

---
### 입력 예시

12

---
### 출력 예시

winter

---
제출
---
```python
a=int(input())
winter=[12,1,2]
spring=[3,4,5]
summer=[6,7,8]
fall=[9,10,11]
if a in winter:
    print("winter")
if a in spring:
    print("spring")
if a in summer:
    print("summer")
if a in fall:
    print("fall")
```

---
### 풀이
* 파이썬에 switch-case가 없어서 아쉽다.
---
