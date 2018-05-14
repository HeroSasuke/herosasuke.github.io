# isspace

|语法|用法|描述|
|:|:|:|
|isspace|mystr.isspace()   |如果 mystr 中只包含空格，则返回 True，否则返回 False.|

实例:

```python
In [36]: mystr = "abc123"

In [37]: mystr.isspace()
Out[37]: False

In [38]: mystr = ""

In [39]: mystr.isspace()
Out[39]: False

In [40]: mystr = " "

In [41]: mystr.isspace()
Out[41]: True

In [42]: mystr = "       "

In [43]: mystr.isspace()
Out[43]: True
```
