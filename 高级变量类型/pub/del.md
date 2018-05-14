# del

|序号 | 方法 |描述|
| :--| :--|:--|
|5	|del(item)	|删除变量|

### 语法
```
del有两种用法，一种是del加空格，另一种是del()
```
### 实例:

```Python
In [20]: a = 1

In [21]: a
Out[21]: 1

In [22]: del a

In [23]: a
---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
<ipython-input-23-60b725f10c9c> in <module>()
----> 1 a

NameError: name 'a' is not defined

In [24]: a = ["a", "b"]

In [25]: del a[0]

In [26]: a
Out[26]: ['b']

In [27]: del a

In [28]: a
---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
<ipython-input-28-60b725f10c9c> in <module>()
----> 1 a

NameError: name 'a' is not defined
```
