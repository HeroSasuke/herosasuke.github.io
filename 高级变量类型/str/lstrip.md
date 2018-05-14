# lstrip

|语法|用法|描述|
|:|:|:|
|lstrip|mystr.lstrip()|删除 mystr 左边的空白字符|

实例:
```Python
In [56]: mystr = "         hello"

In [57]: mystr.lstrip()
Out[57]: 'hello'

In [58]: mystr = "         hello             "

In [59]: mystr.lstrip()
Out[59]: 'hello             '
```
