# 仓库地址

http://10.20.1.51/cdbsc/Mobile-CRM-BSS-D20210225320PF-sc-jkzt-git.git

mvn install:install-file -Dfile=F:\findbugs-maven-plugin-3.0.4.jar -DgroupId=org.codehaus.mojo -DartifactId=findbugs-maven-plugin -Dversion=3.0.4 -Dpackaging=jar



# vm参数

```
-XX:MaxPermSize=512m 
-Dspring.profiles.active=dubbo,web 
-Ddubbo.registry.file=dubbo_portal-web.properties
-Dlog4j.configuration=classpath:log4j-app.xml
```





# 表

## 字典

attr_spec attr_value

STATUS_CD 1100表示无效

删掉一条数据

130	26	不允许	授权操作类型			1100	1100				1									1			



```
let operTypeVals = [
    {"value":"1000","name":"允许","desc":"授权操作类型","nodeList":[]}
];
$("#" + rowid + "_operTypeName").combobox({
    dataSource: operTypeVals,
    dataTextField: 'name',
    dataValueField: 'value',
    value: operTypeVals[0].value,
    editable: false,
    change: function (event) {
    }
});
```

## 角色表

approval_role

根据关键字匹配省市

![image-20211208174737089](C:\Users\19930\AppData\Roaming\Typora\typora-user-images\image-20211208174737089.png)

![image-20211208174820790](C:\Users\19930\AppData\Roaming\Typora\typora-user-images\image-20211208174820790.png)

# 数据流向

## 用户

### 关联角色

新增和删除关联角色=> 同步执行  => 同步到esop系统