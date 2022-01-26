# MyBatis的逆向工程文件

​	当数据库比较复杂的时候，可以使用逆向工程生成数据库中每张表的相关xml文件和实体类，这些文件中可以包含了一些基础的增删改查的操作，可以直接调用，如果是较为复杂的操作或者是表之间的连接操作，则需要自己写出相应的sql语句。

​	文件中的配置可以根据自己的需要进行改动

```xml
<javaModelGenerator targetPackage="com.it.pojo"></javaModelGenerator>
<sqlMapGenerator targetPackage="com.it.mapper"></sqlMapGenerator>
```

配置文件中的这些地方可以根据自己的需要将目标文件夹改为自己需要的位置。