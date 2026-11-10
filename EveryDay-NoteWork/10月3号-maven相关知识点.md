maven 提供了类似 Java 的继承机制，只要将依赖加入到 parent，继承 parent 的项目会自动引入 parent 中的依赖。

maven项目中可以通过<dependencyManagement>来控制子项目是否继承父项目中的依赖.子项目需要导入对应的依赖不用在添加版本号

maven的工程的父模块的pom.xml的打包方式为pom方式，子模块工程的pom.xml的打包方式为jar包方式,需要一致