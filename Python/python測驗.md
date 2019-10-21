# 程式閱讀題
```
1.print("3*2*(17-2)")會印出甚麼結果:
(A)0   (B)90  (C)出現錯誤,無法印出  (D)3*2*(17-2)

2.print(3*2*(17-2))會印出甚麼結果:
(A)0   (B)90  (C)出現錯誤,無法印出  (D)3*2*(17-2)

3.print("abc""+""def")會印出甚麼結果:
(A)出現錯誤,無法印出   (B)abc+def  (C)abc""+""def  (D)abcdef

4.print("abc"+"def")會印出甚麼結果:
(A)出現錯誤,無法印出   (B)abc+def  (C)abc""+""def  (D)abcdef

5.底下程式執行後結果為何?
word = "arttarataaa"
print(word.replace("a", "z",3))
(A)出現錯誤,無法印出   (B)arttarataaa  (C)zrttzrztaaa (D)zrttzrztzzz

6.底下程式執行後結果為何?
word = "arttarataaa"
print(word.replace("a", "z"))
(A)出現錯誤,無法印出   (B)arttarataaa  (C)zrttzrztaaa (D)zrttzrztzzz

7.根據底下程式,下列敘述何者為非?[複選題]
names = ['龍', '聖']
index = 0

while index < len(names): 
    name = names[index]
    print(name)
    index = index + 1
    
(A)len(names)=2  
(B)names[1]是 龍 
(C)程式執行完後,index最後為2
(D)如果把條件改成 index > len(names),中index最後為2

```
# for 迴圈(loop)的技巧
## 程式閱讀題
```
for name in ['orange', 'apple']:
	print(name)

```

```
for index in range(0, 6):
	print(index)

```
## 程式設計題

### 1.使用for 迴圈(loop)計算1+2+3+.....100
```
sum=0
for i in range(1,101):
  sum+=i
print(sum)
```
### 2.使用for 迴圈(loop)計算1+3+5+7.....+99
```
sum=0
for i in range(1,101,2):
  sum+=i
print(sum)
```
### 3.使用for 迴圈(loop)計算1 * 3 * 5 * 7..... * 99
```
sum=1
for i in range(1,101,2):
  sum*=i
print(sum)
```
# while 迴圈(loop)的技巧
## 程式閱讀題
```
index = 0
while index < 1:
	print("Hello, 龍聖")
```
```
index = 0
while index > 1:
	print("Hello, 龍聖")
```
## 程式設計題

### 1.使用while 迴圈(loop)計算1+2+3+.....100
```
i=1
sum=0
while i<101:
  sum+=i
  i+=1
print(sum)
```
### 2.使用while 迴圈(loop)計算1+3+5+7.....+99
```
i=1
sum=0
while i<100:
  sum += i
  i +=2
print(sum)
```
### 3.使用while 迴圈(loop)計算1 * 3 * 5 * 7..... * 99
```
i=1
sum=1
while i<100:
  sum *= i
  i += 2
print(sum)
```



