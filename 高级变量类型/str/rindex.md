# rindex

|语法|用法|描述|
|:|:|:|
|rindex|mystr.rindex( str, start=0,end=len(mystr))|类似于 index()，不过是从右边开始.|

实例:

```python
In [15]: mystr = "hello world itcast and itcastcpp"

In [16]: mystr.rindex("cpp")
Out[16]: 29

In [17]: mystr.rindex("app")
---------------------------------------------------------------------------
ValueError                                Traceback (most recent call last)
<ipython-input-17-cde16cb8ee84> in <module>()
----> 1 mystr.rindex("app")

ValueError: substring not found
```
