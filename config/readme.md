### nacos 配置加载路径

>  配置文件加载顺序

- bootstrap.yml 文件的加载优先级是高于 application.yml 的。
- 如果我们将 Nacos Config 的连接串和参数添加到 bootstrap 文件中，就能确保程序在启动阶段优先执行 Nacos Config 远程配置项的读取任务。这就是我们必须将 Nacos Config 连接串配置在 bootstrap 中的原因
