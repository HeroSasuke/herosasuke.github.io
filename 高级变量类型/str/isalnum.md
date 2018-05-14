# isalnum

|语法|用法|描述|
|:|:|:|
|isalnum|mystr.isalnum()  |如果 mystr 所有字符都是字母或数字则返回 True,否则返回 False|

实例:

```python
In [27]: mystr = "123"

In [28]: mystr.isalnum()
Out[28]: True

In [29]: mystr = "abc"

In [30]: mystr.isalnum()
Out[30]: True

In [31]: mystr = "abc123"

In [32]: mystr.isalnum()
Out[32]: True

In [33]: mystr = "abc_123"

In [34]: mystr.isalnum()
Out[34]: False
```
