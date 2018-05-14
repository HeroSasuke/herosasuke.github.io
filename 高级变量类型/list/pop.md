# pop

<table>
    <tr>
      <td><b>语法</b></td>
      <td><b>用法</b></td>
      <td><b>描述</b></td>
   </tr>
    <tr>
        <td rowspan="2">pop</td>    
        <td >list.pop(index)</td>  
        <td >设置参数，则会删除指定索引对应的数据,pop有返回值，返回值就是要删除的那个元素的值</td>  
    </tr>
    <tr>
        <td >list.pop()</td>  
        <td >不设置参数时，会将列表中最后一个元素删除,pop有返回值，返回值就是要删除的那个元素的值</td>  
    </tr>
</table>

### list.pop(index)

- 设置参数，则会删除指定索引对应的数据,pop有返回值，返回值就是要删除的那个元素的值

- 实例:
  ```python
  namelist = ["zhangsan", "lisi", "wangwu", "zhaoliu"]

  popname = namelist.pop(0)

  print(popname)
  print(namelist)

  ```
- 运行结果
  ```
  zhangsan
  ['lisi', 'wangwu', 'zhaoliu']
  ```

### list.pop()

- 不设置参数时，会将列表中最后一个元素删除,pop有返回值，返回值就是要删除的那个元素的值
- 实例:
  ```python
  namelist = ["zhangsan", "lisi", "wangwu", "zhaoliu"]

  popname = namelist.pop()

  print(popname)
  print(namelist)
  ```
- 运行效果:
  ```
  zhaoliu
  ['zhangsan', 'lisi', 'wangwu']
  ```
