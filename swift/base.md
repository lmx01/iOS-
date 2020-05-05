# 1.1 base.md

Swift文档：
https://github.com/SwiftGGTeam/the-swift-programming-language-in-chinese

小马哥视频教材：
https://www.bilibili.com/video/BV1qJ411B7G3?from=search&seid=5618679441091610999

1. 定义变量

```swift
// 格式：let/var 标识符名称 ： 标识符类型 = 赋值
// let常量
// var变量
var a : Int = 20

let b : Double = 3.14
// b = 2.44 错误

// 常量本质：指向的内存地址不可以修改，指向的对象属性可以修改
let view : UIView = UIView()
// view = UIView() 错误

view.alpha = 0.5
view.backgroundColor = UIColor.blue
```

(学到P34)