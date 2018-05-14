# break和continue

## break

### for循环

- 普通的for循环:

  ```Python
  name = "Python"

  for x in name:
      print("*******")
      print(x)
  ```

  执行结果:

  ```
  *******
  P
  *******
  y
  *******
  t
  *******
  h
  *******
  o
  *******
  n
  ```
- 带有break的for循环:

  ```Python
  name = "Python"

  for x in name:
      print("*******")
      if x == "t":
          break
      print(x)
  ```

  执行结果:

  ```
  *******
  P
  *******
  y
  *******
  ```

### while循环:

- 普通的while循环如下:
  ```Python
  i = 1

  while i <= 5:

      print("******")
      print(i)
      i += 1
  ```

  执行结果:

  ```
  ******
  1
  ******
  2
  ******
  3
  ******
  4
  ******
  5
  ```

- 带有break的while循环:

  ```Python
  i = 1

  while i <= 5:

      print("******")

      if i == 3:
          break
      print(i)
      i += 1
  ```
  执行结果:

  ```
  ******
  1
  ******
  2
  ******
  ```

### 总结:

- <font color='red'>break的作用：用来结束break所在的整个循环</font>

## continue

### for循环  

- 带有continue的for循环

  ```Python
  name = 'Python'

  for x in name:
      print('----')
      if x == 't':
          continue
      print(x)
  ```
运行结果:
  ```
  ----
  P
  ----
  y
  ----
  ----
  h
  ----
  o
  ----
  n
  ```

### while循环

- 带有continue的while循环：

  ```Python
  i = 1

  while i <= 5:
      i = i+1
      print('----')
      if i == 3:
          continue
      print(i)
  ```

  执行效果:

  ```
  ----
  2
  ----
  ----
  4
  ----
  5
  ----
  6
  ```

### 小结:
- <font color='red'>continue的作用：用来结束本次循环，紧接着执行下一次的循环</font>

## <font color='red'>注意点</font>

- break/continue只能用在循环中，除此以外不能单独使用

- break/continue在嵌套循环中，只对最近的一层循环起作用
