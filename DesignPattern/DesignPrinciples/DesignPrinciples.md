#  Design Principles

## SOLID

### 单一职责 Single Responsibility Principle
对象应该具有一种单一功能的概念

应用：
1、UIView 跟 CALayer 职责分离，UIView 负责事件交互，CALayer 负责管理图层


### 开闭原则 Open Close Principle
软件应该是对扩展开放，对修改封闭的

应用：
1、分类，可以在分类中添加功能，但不影响原类


### 里氏替换原则 Liskov Substitution Principle
程序中的对象应该是可以在不改变程序正确性的前提下被它的子类所替换

应用：
1、KVO


### 接口隔离原则 Interface Segregation Principle
多个特定的接口要好于一个宽泛用途的接口

应用：
1、UITableView 的 delegate 和 dataSource


### 依赖倒置原则 Dependency Inversion Principle
依赖于抽象而不是一个实例
代码应该取决于抽象概念，而不是具体概念
依赖注入一个对象时，可以依赖这个对象的协议（抽象），而不是依赖对象自身。方便扩展，也方便解耦

应用：
1、协议，通过协议交互，而不是具体实例

