This is a Windows port of Snappy compression algorithm.

Website: [Snappy for Windows](http://snappy.angeloflogic.com/)

直接生成的动态链接库在调用时会报错，在属性中改为静态链接库，同时注意生成和调用项目的属性中
c/c++-》代码生成-》运行库属性是否一致
