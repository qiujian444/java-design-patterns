## 复合模式结合两个或以上的模式,组成一个解决方案，解决一再发生的一般性问题

#### MVC模式是一个复合模式,由策略模式、观察者模式、组合模式组成。  具体分为model1和model2两种情形。  
    1、model1是比较教科书化的,能明确的体现出三种模式的混合应用。  
    2、model2是我们平常知道的,且频繁使用的一种模式(Spring MVC框架)  

#### 但是不管是哪一种模式,其具体思路都是如下内容:  
    MVC 模式代表 Model-View-Controller（模型-视图-控制器） 模式。这种模式用于应用程序的分层开发。
    Model（模型） - 模型代表一个存取数据的对象或 JAVA POJO。它也可以带有逻辑，在数据变化时更新控制器。
    View（视图） - 视图代表模型包含的数据的可视化。
    Controller（控制器） - 控制器作用于模型和视图上。它控制数据流向模型对象，并在数据变化时更新视图。它使视图 与模型分离开。
![MVC图示](MVC.png)

具体的细节看内部示例图与代码