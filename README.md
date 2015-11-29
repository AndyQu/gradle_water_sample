# gradle_water_sample
这个工程是gradle多工程构建的示例。Gradle的构建过程包括三个步骤：初始化阶段、配置阶段、执行task阶段。
## 初始化阶段
    gradle决定构建过程包括哪些project；然后为每一个project创建一个project meta model。
## 配置阶段
    gradle执行每一个project的build.gradle文件。
    每个project的属性，所包含的task，task之间的依赖关系等等。各个project之间的依赖关系等等。都会被配置好。
## 执行阶段
    根据用户指定的task，gradle计算出需要被执行的task DAG，然后执行每一个task。
