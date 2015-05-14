# RainbowDemo
在Xcode6中使用IBDesignable创建自定义控件

[教程地址](http://www.jianshu.com/p/18b10ed2acd5)

在Xcode的旧版本中，试图创建一个自定义控件，并不是很容易，因为在IB中，并不能实时预览到你的设计成果，只能在模拟器中测试。对于设计一个单一组件，可能需要花费大量时间。

Xcode6的发布，苹果为开发者构建自定义控件推出了新功能**IBDesignable**和**IBInspectable**，允许在IB中实时预览设计成果。很明显，这是一个巨大的生产力效益。

在本教程中，将介绍IBDesignable IBInspectable，以及展示如何利用这个新功能。除过创建demo示例没有更好地方式来阐述这一新特性，因此，创建一个"Rainbow"自定义界面。

![效果图](http://i1.tietuku.com/a476b2f40c2465d0.png)
