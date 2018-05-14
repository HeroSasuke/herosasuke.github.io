# split

|语法|用法|描述|
|:|:|:|
|split|mystr.split(str=" ", 2) |以 str 为分隔符切片 mystr，如果 maxsplit有指定值，则仅分隔 maxsplit 个子字符串|

实例:

```python
In [23]: name = "hello python ha ha"

In [24]: name.split(" ")
Out[24]: ['hello', 'python', 'ha', 'ha']

In [25]: name.split(" ", 2)
Out[25]: ['hello', 'python', 'ha ha']
```
