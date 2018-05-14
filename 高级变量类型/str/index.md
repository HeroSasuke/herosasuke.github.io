# index

|语法|用法|描述|
|:|:|:|
|index|mystr.index(str, start=0, end=len(mystr)) |跟find()方法一样，只不过如果str不在 mystr中会报一个异常.|

实例:

```Python
In [11]: mystr = 'hello world itcast and itcastcpp'

In [12]: mystr.find("itcast", 0, 10)
Out[12]: -1

In [13]: mystr.index("itcast")
Out[13]: 12

In [14]: mystr.index("itcast", 0, 10)
---------------------------------------------------------------------------
ValueError                                Traceback (most recent call last)
<ipython-input-14-7cdc287c07b2> in <module>()
----> 1 mystr.index("itcast", 0, 10)

ValueError: substring not found
```
