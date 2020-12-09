# day13

```
s = input('请输入一个字符串：')
if not s:
    print('请不要输入空字符串！')
    s = input('请重新输入一个字符串：')

a = len(s)
i = 0
count = 1    
while i <= (a/2):
    if s[i] == s[a-i-1]:
        count = 1
        i += 1
    else:
        count = 0
        break

if count == 1:
    print('您所输入的字符串是回文')
else:
    print('您所输入的字符串不是回文')
    ```
    ```
    s = input('请输入一个字符串：')
if not s:
    print('请不要输入空字符串！')
    s = input('请重新输入一个字符串：')

a = reversed(list(s))
if list(a) == list(s):
    print('您所输入的字符串是回文')
else:
    print('您所输入的字符串不是回文')
    ```
    https://www.taiwancodeschool.com/single-post/2018/09/05/Python-for-while
```
break
```
==and=之差
=是一樣
==是判斷


