# rpartition

|语法|用法|描述|
|:|:|:|
|rpartition|mystr.rpartition(str)|类似于 partition()函数,不过是从右边开始.|

实例:

```python
In [5]: mystr = "hello world itcast and itcastcpp"

In [6]: mystr.rpartition("itcast")
Out[6]: ('hello world itcast and ', 'itcast', 'cpp')
```
