# 虚方法

##定义： 要求在继承中，子类重写的方法的`方法名`，`返回值类型`、`参数列表`相同。

    
在一个基类函数声明为 `virtual` 就可以在任何派生类中重写该函数
    
```c#
class BaseClass {
    public virtual string VirtualMethod (){
        return "Method is base class";
    }
}
```

在派生类中重写另一个函数时，要使用 `override` 关键字 显示声明

```C#
class override string VirtualMethod(){
    return "Method is called in derivedclass"
}
```
