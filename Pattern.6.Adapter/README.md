# 适配器模式

适配器模式（Adapter Pattern）是作为两个不兼容的接口之间的桥梁，属于结构型模式。

## 优点

1. 让两个没有关联的类一起运行
2. 提高了类的服用
3. 增加了类的透明度
4. 灵活性好

## 缺点

1. 过多使用适配器，会使系统非常凌乱
2. 在单继承局限中，适配器只能适配一个适配者类，且必须是抽象类

## 注意事项

> 适配器用来解决正在服役项目的问题，最好不用用于新设计系统