# designpattern
1. 第一版完整工厂模式
2. 第二版抽象工厂模式， 增加了工厂分族， 大陆工厂， 香港工厂
3. 策略模式及策略模式与简单工厂相结合
4. 模板方法模式: 把大象装到冰箱里共分几步
5. 委托模式: boss(委托人): 我是想点子的;  leader(被委托人):我是分任务的; empls: 我们才是受苦的
6. 适配器模式: 如何把usb插入到插座里
7. 装饰者模式: 别以为穿马甲我就不认识你了, io流
8. 观察者模式及事件委托机制
9. 代理模式
+ 静态代理:要做的事情已经是确定的, 只是表面上换了个人去做,代理对象和被代理对象实现同样的接口,实际通过传入对象调用
+ jdk动态代理: 与静态代理效果相同, 但是java通过反射实现代理类不用实现与被代理对象同样的接口, 也可以根据传入方法调用被代理对象的方法, 传入对象调用
+ cglib动态代理: 只需要传入被代理对象的类名, 内部会实现创建对象到调用的过程,客户端不需要创建具体的对象, 接口调用方法
