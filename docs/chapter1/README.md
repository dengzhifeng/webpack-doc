# Webpack 的配置参数

从这一章开始我们就来详细的讲一下 `webpack` 的配置参数，算上配置项，loader 的配置项，plugins 的配置项，加载一起，超过几万个那是妥妥的，我们想要把这些都给记住肯定是不可能。因此我们就首先学会核心的一些知识点，其他的当我们碰到问题的时候再去查阅相关的文档，这是一个相对来说，比较好的方法。



如果按照配置所影响的功能来划分的话，我们可以将配置分成下面的内容：

* Entry：配置模块入口
* Output：配置如何输出最终想要的代码
* Module：配置处理模块的规则
* Resolve：配置寻找模块的规则
* Plugins：配置扩展插件
* DevServer：配置DevServer，就是起一个服务
* 其他配置项：其他零散的配置项
* 整体配置结构：整体的描述各配置项的结构
* 多种配置类型：配置文件不不止可以返回一个 Object，还可以返回其他格式
* 配置总结：寻找配置Webpack 的规则，减少思维负担。
