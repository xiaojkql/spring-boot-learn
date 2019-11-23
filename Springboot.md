ymal语法规则
@ConfigurationProperties和@Value两种获取值的方法
@PropertyResource: 告诉我们properties配置文件的位置

@ImportResource: 导入我们的配置文件的位置(Spring allication-context.xml)
@Configuration (配置类，里面有方法返回bean, java方式配置bean)

在Controller中返回视图模板时不需要第一个斜杆
返回链接映射时需要返回第一个斜杆
在html中使用th:href th:src 需要带上第一个斜杆
不能直接用null != null进行判断，应该先声明一个Object对象，然后用这个对象的实例与null进行比较判断

公共资源用webjars
自己的资源用static

要进行跳转必须使用<a标签>
