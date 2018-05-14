# pop

| 语法    | 用法     | 描述|
| :------------- | :------------- |:------------- |
|pop|dict.pop(key)|删除指定的键值对，key 不存在会报错，设置默认值|

实例:
```python
In [63]: infos = {"name": "zhangsan", "age": 18, "gender": "男"}

In [64]: infos.pop("name")
Out[64]: 'zhangsan'

In [65]: infos
Out[65]: {'age': 18, 'gender': '男'}

In [66]: infos.pop("classes")
---------------------------------------------------------------------------
KeyError                                  Traceback (most recent call last)
<ipython-input-66-61f77cea8121> in <module>()
----> 1 infos.pop("classes")

KeyError: 'classes'

In [67]: infos.pop("classes", "Python8期")
Out[67]: 'Python8期'
```
