# sort
<table>
    <tr>
        <td><b>语法</b></td>
        <td><b>用法</b></td>
        <td><b>描述</b></td>
   </tr>
    <tr>
        <td rowspan="4">sort</td>    
        <td >list.sort()</td>  
        <td >默认升序，从小到大排序</td>  
    </tr>
    <tr>
        <td >list.sort(key=int)</td>  
        <td>  可以将形似数字的字符串参与数字的排序  </td>
    </tr>
    <tr>
        <td >list.sort(key=len)</td>  
        <td>  可以比较字符串的长度 </td>
    </tr>
    <tr>
        <td >list.sort(reverse=True) </td>  
        <td>  降序， 从大到小</td>
    </tr>  
</table>


### list.sort()

- 默认升序，从小到大排序
- 实例:

  ```python
  numlist = [3, 1, 4, 6, 2, 9, 10]

  numlist.sort()

  print(numlist)
  ```
- 运行结果:

  ```python
  [1, 2, 3, 4, 6, 9, 10]
  ```

### list.sort(key=int)

- 可以将形似数字的字符串参与数字的排序
- 实例:
  ```python
  numlist = ["3", "1", "4", "6", "2", "9", "10"]

  numlist.sort(key=int)

  print(numlist)
  ```
- 运行结果:
  ```python
  ['1', '2', '3', '4', '6', '9', '10']
  ```

### list.sort(key=len)
- 可以比较字符串的长度
- 实例:

  ```python
  namelist = ["zhangsan", "lisi", "wangwu", "zhaoliu"]

  namelist.sort(key=len)

  print(namelist)
  ```
- 运行结果:

  ```python
  ['lisi', 'wangwu', 'zhaoliu', 'zhangsan']
  ```

### list.sort(reverse=True)
- 降序， 从大到小
- 实例:
  ```python
  namelist = [4, 2, 1, 5, 10, 9, 8, 6]

  namelist.sort(reverse=True)

  print(namelist)
  ```
- 运行结果:
  ```python
  [10, 9, 8, 6, 5, 4, 2, 1]
  ```
