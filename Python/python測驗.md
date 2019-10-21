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

```
# 程式設計題

## for 迴圈(loop)的技巧

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
## while 迴圈(loop)的技巧

### 3.使用while 迴圈(loop)計算1+2+3+.....100
```
i=1
sum=0
while i<101:
  sum+=a
  i+=1
print(sum)
```
### 4.使用while 迴圈(loop)計算1+3+5+7.....+99
```
i=1
sum=0
while i<100:
  sum += a
  i +=2
print(sum)
```
