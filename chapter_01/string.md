## 2 变量和简单数据类型。

### 2.1 

### 2.2 

### 2.3 字符串

- 字符串类型，允许用单引号和双引号引起的都是字符串，如下：
```python
'This is a string type'
"this is a string type"
```
- 这种特性可以让你在字符串中使用单引号和双引号。如下：
```python
'This is a string type, "hello,world"'
"this is a string type, 'hello,world'"
```

#### 2.3.1 使用方法修改字符串的大小写。

- 可以使用 ***title()*** 来修改字符串为大写。注意该方法是字符串类的方法，所以使用方式遵循 ***变量名.title()*** 的方式，如下
```python
name = "ada lovelace"
print(name.title())
