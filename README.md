# 《深入理解Java核心技术（基础篇》勘误

亲爱的读者们，欢迎大家对本书内容进行勘误，如您在本书中发现需要修改的地方，请通过提交Issue的方式告知我们，谢谢


## 第二章

### 19页

当编写一个可实例化的类时，如果没有专门编写构造函数，那么多数......Interge -> null 

和下一段有重复，需要删除本段。

### 21页

而对于线程c和d，  改为 "而对于变量c和d"

## 第六章

### 58页

https://github.com/hollischuang/In-depth-Understanding-Of-The-Core-Java/issues/2

## 第七章

### 67页

“原因就是和Integer中的缓存机制有关....如果数字在128至127之间，” 这里的128应该为-128。

## 第八章

### 81页

代码段中第三行注释“使用replace将a替换成H”，应该改为"使用replaceAll将a替换成H"

### 86页

”查看StringUtils.join的源代码....它也是通过StringBuilde实现...  “这里的StringBuilde应该替换为StringBuilder


### 110页

可以看到，在Class文件的.... Holl、s888这六个常量。其中"s888"为笔误，应该是"is888"

### 116 

但s2.intern()会从池中取出已有的引用，这就和s2相等了，这里应该是和s1相等了

## 第九章

### 140页

以上代码的输出结果为3，这里应该改为'以上代码的输出结果为2'

### 142页

图10-1 ，interface和class的颜色标反了



## 第十章

### 147页

Map遍历中通过key找value遍历，key和value类型都应为string，即 Integer value = map.get(key) 中的Integer需要改为String

### 233页

"相比于非阻塞队列.....而非阻塞队列虽然安全性不如非阻塞队列..."  修改为 "相比于非阻塞队列.....而非阻塞队列虽然安全性不如阻塞队列..." 

https://github.com/hollischuang/In-depth-Understanding-Of-The-Core-Java/issues/1

## 第13章

### 311页

4枚举可解决反序列化会破坏单例模式的问题
……
第二段：在 13.4 节中介绍过，……
应该是：在 13.5 节……

## 第18章

### 388页

最后一段代码的注释中 Data 应该改为 Date

### 399页

顶部第3点

……
……
……，而1.1、1.2、1.3 才属于2020年，1.4 周日是下一周的开始，所以第一周应该只有1.1、1.2、1.3这三天

应是：

……，而1.1、1.2、1.3、1.4 才属于2020年，1.5 周日是下一周的开始，所以第一周应该只有1.1、1.2、1.3、1.4这四天

https://github.com/hollischuang/In-depth-Understanding-Of-The-Core-Java/issues/5

