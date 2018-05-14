# len

|序号 | 方法 |描述|
| :--| :--|:--|
|2	|len(item)	|返回对象(字符串、列表、元组、字典等)长度或者项目个数|

### 描述
```
Python  len()方法返回对象(字符串、列表、元组、字典等)长度或者项目个数
```

### 语法

```
len(object)
```

### 参数
- object : 对象

### 返回值
```
返回对象的长度
```

### 实例
```Python
In [34]: mystr = "helloworld"

In [35]: len(mystr)
Out[35]: 10

In [36]: mylist = [1, 2, 3, 4, 5]

In [37]: len(mylist)
Out[37]: 5

In [38]: mytuple = (1, 2, 3, 4, 5)

In [39]: len(mytuple)
Out[39]: 5

In [40]: mydist = {"name": "zhansgan", "age": 18}

In [41]: len(mydist)
Out[41]: 2
```
