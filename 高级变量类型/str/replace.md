# replace

|语法|用法|描述|
|:|:|:|
|replace|mystr.replace(str1,str2,mystr.count(str1))|把 mystr 中的 str1 替换成 str2,如果 count 指定，则替换不超过 count 次.|

实例:

```Python
In [19]: name = "hello ha ha"

In [20]: name.replace("ha", "Ha")
Out[20]: 'hello Ha Ha'

In [21]: name.replace("ha","Ha",1)
Out[21]: 'hello Ha ha'
```
