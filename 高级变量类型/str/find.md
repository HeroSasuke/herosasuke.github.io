# find

|语法|用法|描述|
|:|:|:|
|find|mystr.find(str,start=0,end=len(mystr))|检测 str 是否包含在 mystr中，如果是返回开始的索引值，否则返回-1|

实例:

```Python
In [2]: mystr = 'hello world itcast and itcastcpp'

In [3]: mystr.find("itcast")
Out[3]: 12

In [4]: mystr.find("itcast",0, 10)
Out[4]: -1
```
