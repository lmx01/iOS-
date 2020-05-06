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

2. 数据类型

3. 类型推导
  强类型语言

  ```swift
  // 定义标识符时，有直接赋值，可以将后面的类型省略掉
  // 通过option + 鼠标左键 来查看标识符类型
  let a = 20
  var b = 2.44
  ```

4. 基本运算
  相同类型才可以进行运算

  ```swift
  let m = 20
  let n = 10.5

  // let result = m + n 错误
  let result1 = Double(m) + n
  let result2 = m + Int(n)
  ```

5. 逻辑分支

  - if

    ```
    let a= 10
    // 没有非零即真
    if a > 0 {
      print("a大于0")
    } else if a < -10 {
      pirnt("a小于0")
    }
  ```

  - guard

    ```
    guard 条件表达式 else {
      //条件语句
      break
    }  
    语句组
    ```

    ```

    ```
