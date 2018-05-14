# isdigit

|语法|用法|描述|
|:|:|:|
|isdigit|mystr.isdigit() |如果 mystr 只包含数字则返回 True 否则返回 False.|

实例:

```python
In [20]: mystr = "abc"

In [21]: mystr.isdigit()
Out[21]: False

In [22]: mystr = "123"

In [23]: mystr.isdigit()
Out[23]: True

In [24]: mystr = "abc123"

In [25]: mystr.isdigit()
Out[25]: False
```
