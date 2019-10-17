## 类图学习

#### 建模概要

模型是对某种系统的抽象，其目的是在构建这个系统之前先理解它，常见的三种建模设计技术包括类建模、状态建模、交互建模。这三种建模技术从不同的角度描述了系统的不同层面，类模型表现了系统静态化的、结构化的“数据层面”；状态模型表现了系统时序的、行为的“控制层面”；交互模型表现了系统各个对象的“交互层面”

类模型通过描述系统内部类的属性、操作及与其他类的相互关系来捕获系统的静态结构。类模型是三种模型中最重要的，也是最常用的。

#### 类图

常见的类图存在着六大关系：实现(realization)、继承(也叫泛化)(generalization)、依赖(dependency)、关联(association)、聚合(aggregation)、组合(composition)

> 实现

是指一个类`class`实现了某个`interface`接口，一般语言通过`implements`关键字表明两者的关系，在图形中使用虚线中空箭头表示，由类指向接口。