# del

| 语法    | 用法     | 描述|
| :------------- | :------------- |:------------- |
|del|del dict[key]|删除指定的键值对，key不存在会报错|

实例：
```python
In [58]: infos = {"name": "zhangsan", "age": 18, "gender": "男"}

In [59]: del infos["gender"]

In [60]: infos
Out[60]: {'age': 18, 'name': 'zhangsan'}

In [61]: del infos["classees"]
---------------------------------------------------------------------------
KeyError                                  Traceback (most recent call last)
<ipython-input-61-5bfdca3679fa> in <module>()
----> 1 del infos["classees"]

KeyError: 'classees'
```
