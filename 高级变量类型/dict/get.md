# get

| 语法    | 用法     | 描述|
| :------------- | :------------- |:------------- |
|get|dict.get(key)|根据键从字典中取值，key不存在不会报错  默认值 None|

实例:

```python
In [11]: infos = {"name": "zhangsan", "age": 18, "gender": "男"}

In [12]: infos.get("name")
Out[12]: 'zhangsan'

In [13]: infos.get("age")
Out[13]: 18

In [14]: infos.get("classes")

In [15]:

```
