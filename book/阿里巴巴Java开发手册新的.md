[2018-9-24]

一、编程规约

（一）命名风格

1 ok。不能使用下划线或美元符号

2 ok。拼音和英文混合。

3 ok。类名使用UpperCamelCase风格，DO、BO、DTO、VO、AO、PO、UID除外，这几个不熟悉。

4 ok。 方法名、参数、成员变量、局部变量同意使用lowerCamelCase风格。

5 ok。常量命名全部大写加下划线。

6 part。 抽象类使用Abstract或Base开头，异常类名使用Exception结尾，测试类使用测试类名称，以Test结尾。

7 part。类型与中括号紧挨相连来表示。

8 part。

9 part。

10 ok。

11 ok。

12 ok。

13 ok。

14 part。

15 part. 枚举类名建议带上Enum后缀，枚举成员需要全大写，单词间下划线。

16 part

(二)常量定义
1. ok.不允许任何魔法值。
2. part。long或Long赋值，数值后用大写L，不能是小写l。
3. part。不适用一个常量类维护所有变量，要按常量功能进行归类。
4. part。
5. part。变量值在一个固定范围内变化，使用enum定义。

（三）代码格式
1. ok。
2. ok。
3. ok。
4. ok。
5. ok。采用4个空格缩进，禁止使用tab字符。
6. ok。双划线与注释内容之间仅有一个空格。
7. part。单行不超过120个。
8. ok。 多个参数逗号必须加空格。
9. ok. ide文本使用utf-8，unix格式
10. ok。 单个方法的总行数不超过80行。
11. ok。
12. ok。不同逻辑、不他那个语义、不同业务的代码之间插入一个空行。

（四）OOP规约
1. part.
2. ok.
3. part.
4. part.
5. ok.
6. part. 推荐使用Jdk7的java.util.Objects#equals
7. part.
8. ok. pojo,rpc使用包装类，局部变量使用基本类型。
9. part。 DO、DTO、VO等Pojo，不需要任何属性默认值。
10. part。序列号类新增属性，不能修改serialVersionUID，避免反序列失败。







