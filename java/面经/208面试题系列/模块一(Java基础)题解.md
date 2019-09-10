1. JDK和JRE有什么区别？
```
JDK:Java Development Kit ，java开发工具包，包含JRE和一些工具
JRE:Java Runtime Environment，运行时环境，包含虚拟机，基础类库
```
2. ==和equals的区别是什么？
```
==是引用地址的比较
equals是值比较
```
3. 两个对象的hashCode相同，则equals()也一定为true，对吗？
```
不一定
不同值的hashCode是有可能相同的
```
4. final在java中有什么作用?
```
修饰类，类不可被继承
修饰属性，属性值不可被修改
修饰方法，方法不可被重写
```
5. java中的Math.round(-1.5)等于多少?
```
-1
判定过程:-2.0,-1.9,-1.8,-1.7,-1.6,-1.5,-1.4,-1.3,-1.2,-1.1,-1.0
		1.0,  1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8, 1.9, 2.0
```
6. String 属于基础数据类型吗？
```
不属于，
基础数据类型有：byte(1),short(2),int(4),long(8),float(4),double(8),boolean(1),char(1)
```
7. java中操作字符串都有哪些类？他们之间有什么区别？
```
String、StringBuilder、StringBuffer
String每次都会创键一块新的内存空间来存储字符串并且String中的内容不会被改变
StringBuilder是线程不安全的，但是单线程条件下效率比StringBuffer高
StringBuffer是线程安全的
```
8. String str = "i" 与String str = new String("i")一样吗？
```
不一样
前者是存放在字符串常量池中，后者是堆区新开辟了一块内存区域
```
9. 如何将字符串反转？
```
使用reverse()方法
toCharArray()再倒序输出
```
10. String 类的常用方法都有哪些？
```
equals()、equalsIgnoreCase()、split()、contains、substring()、startWith()、endWith()、toLowerCase()、toUpperCase()、charAt()、replace()、trim()、indexOf()、getBytes()、length()
```
11. 抽象类必须要有抽象方法吗？
```
不是
抽象类可以同时包含抽象类和具体实现类，不是必须要有抽象方法
```
12. 普通类和抽象类有哪些区别？
```
普通类不可包含抽象方法，普通类的方法必须要有方法体，普通类可以被final修饰符修饰，普通类实现接口时必须实现其方法；
抽象类实现接口时不必实现其方法，不可被final修饰
```
13. 抽象类能使用final修饰吗？
```
不能
```
14. 接口和抽象类有什么区别？
```
抽象类只能被继承，抽象类可以有具体的方法实现
接口只能被实现，普通类可以同时实现多个接口的方法
```
15. java中IO流分为几种？
```
输入、输出流
字节、字符流
```
16. BIO、NIO、AIO有什么区别？
```
BIO 同步阻塞
NIO	同步非阻塞
AIO 异步非阻塞
```
17. Files的常用方法都有哪些？
```
createDirectories()、copy()、isFile()、isDirectory()、delete()
```
