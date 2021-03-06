# Summary

* [Introduction](README.md)
* [前言](preface.md)

## 第一部分：学习 Go 语言

* [第1章：Go 语言的起源，发展与普及](di-1-zhang-ff1a-go-yu-yan-de-qi-yuan-ff0c-fa-zhan-yu-pu-ji.md)
  * [起源与发展](01.1.md)
  * [语言的主要特性与发展的环境和影响因素](01.2.md)
* [第2章：安装与运行环境](di-2-zhang-ff1a-an-zhuang-yu-yun-xing-huan-jing.md)
  * [平台与架构](02.1.md)
  * [Go 环境变量](02.2.md)
  * [在 Linux 上安装 Go](02.3.md)
  * [在 Mac OS X 上安装 Go](02.4.md)
  * [在 Windows 上安装 Go](02.5.md)
  * [安装目录清单](02.6.md)
  * [Go 运行时（runtime）](02.7.md)
  * [Go 解释器](02.8.md)
* [编辑器、集成开发环境与其它工具](03.0.md)
  * [Go 开发环境的基本要求](03.1.md)
  * [编辑器和集成开发环境](03.2.md)
  * [调试器](03.3.md)
  * [构建并运行 Go 程序](03.4.md)
  * [格式化代码](03.5.md)
  * [生成代码文档](03.6.md)
  * [其它工具](03.7.md)
  * [Go 性能说明](03.8.md)
  * [与其它语言进行交互](03.9.md)

## 第二部分：语言的核心结构与技术

* 第4章：基本结构和基本数据类型
  * [文件名、关键字与标识符](04.1.md)
  * [Go 程序的基本结构和要素](04.2.md)
  * [常量](04.3.md)
  * [变量](04.4.md)
  * [基本类型和运算符](04.5.md)
  * [字符串](04.6.md)
  * [strings 和 strconv 包](04.7.md)
  * [时间和日期](04.8.md)
  * [指针](04.9.md)
* [控制结构](05.0.md)
  * [if-else 结构](05.1.md)
  * [测试多返回值函数的错误](05.2.md)
  * [switch 结构](05.3.md)
  * [for 结构](05.4.md)
  * [Break 与 continue](05.5.md)
  * [标签与 goto](05.6.md)
* [函数（function）](06.0.md)
  * [介绍](06.1.md)
  * [函数参数与返回值](06.2.md)
  * [传递变长参数](06.3.md)
  * [defer 和追踪](06.4.md)
  * [内置函数](06.5.md)
  * [递归函数](06.6.md)
  * [将函数作为参数](06.7.md)
  * [闭包](06.8.md)
  * [应用闭包：将函数作为返回值](06.9.md)
  * [使用闭包调试](06.10.md)
  * [计算函数执行时间](06.11.md)
  * [通过内存缓存来提升性能](06.12.md)
* [数组与切片](07.0.md)
  * [声明和初始化](07.1.md)
  * [切片](07.2.md)
  * [For-range 结构](07.3.md)
  * [切片重组（reslice）](07.4.md)
  * [切片的复制与追加](07.5.md)
  * [字符串、数组和切片的应用](07.6.md)
* [Map](08.0.md)
  * [声明、初始化和 make](08.1.md)
  * [测试键值对是否存在及删除元素](08.2.md)
  * [for-range 的配套用法](08.3.md)
  * [map 类型的切片](08.4.md)
  * [map 的排序](08.5.md)
  * [将 map 的键值对调](08.6.md)
* [包（package）](09.0.md)
  * [标准库概述](09.1.md)
  * [regexp 包](09.2.md)
  * [锁和 sync 包](09.3.md)
  * [精密计算和 big 包](09.4.md)
  * [自定义包和可见性](09.5.md)
  * [为自定义包使用 godoc](09.6.md)
  * [使用 go install 安装自定义包](09.7.md)
  * [自定义包的目录结构、go install 和 go test](09.8.md)
  * [通过 Git 打包和安装](09.9.md)
  * [Go 的外部包和项目](09.10.md)
  * [在 Go 程序中使用外部库](09.11.md)
* [结构（struct）与方法（method）](10.0.md)
  * [结构体定义](10.1.md)
  * [使用工厂方法创建结构体实例](10.2.md)
  * [使用自定义包中的结构体](10.3.md)
  * [带标签的结构体](10.4.md)
  * [匿名字段和内嵌结构体](10.5.md)
  * [方法](10.6.md)
  * [类型的 String\(\) 方法和格式化描述符](10.7.md)
  * [垃圾回收和 SetFinalizer](10.8.md)
* [接口（interface）与反射（reflection）](11.0.md)
  * [接口是什么](11.1.md)
  * [接口嵌套接口](11.2.md)
  * [类型断言：如何检测和转换接口变量的类型](11.3.md)
  * [类型判断：type-switch](11.4.md)
  * [测试一个值是否实现了某个接口](11.5.md)
  * [使用方法集与接口](11.6.md)
  * [第一个例子：使用 Sorter 接口排序](11.7.md)
  * [第二个例子：读和写](11.8.md)
  * [空接口](11.9.md)
  * [反射包](11.10.md)
  * [Printf 和反射](11.11.md)
  * [接口与动态类型](11.12.md)
  * [总结：Go 中的面向对象](11.13.md)
  * [结构体、集合和高阶函数](11.14.md)

## 第三部分：Go 高级编程

* [读写数据](12.0.md)
  * [读取用户的输入](12.1.md)
  * [文件读写](12.2.md)
  * [文件拷贝](12.3.md)
  * [从命令行读取参数](12.4.md)
  * [用 buffer 读取文件](12.5.md)
  * [用切片读写文件](12.6.md)
  * [用 defer 关闭文件](12.7.md)
  * [使用接口的实际例子：fmt.Fprintf](12.8.md)
  * [格式化 JSON 数据](12.9.md)
  * [XML 数据格式](12.10.md)
  * [用 Gob 传输数据](12.11.md)
  * [Go 中的密码学](12.12.md)
* [错误处理与测试](13.0.md)
  * [错误处理](13.1.md)
  * [运行时异常和 panic](13.2.md)
  * [从 panic 中恢复（Recover）](13.3.md)
  * [自定义包中的错误处理和 panicking](13.4.md)
  * [一种用闭包处理错误的模式](13.5.md)
  * [启动外部命令和程序](13.6.md)
  * [Go 中的单元测试和基准测试](13.7.md)
  * [测试的具体例子](13.8.md)
  * [用（测试数据）表驱动测试](13.9.md)
  * [性能调试：分析并优化 Go 程序](13.10.md)
* [协程（goroutine）与通道（channel）](14.0.md)
  * [并发、并行和协程](14.1.md)
  * [使用通道进行协程间通信](14.2.md)
  * [协程同步：关闭通道-对阻塞的通道进行测试](14.3.md)
  * [使用 select 切换协程](14.4.md)
  * [通道，超时和计时器（Ticker）](14.5.md)
  * [协程和恢复（recover）](14.6.md)
  * [新旧模型对比：任务和worker](14.7.md)
  * [惰性生成器的实现](14.8.md)
  * [实现 Futures 模式](14.9.md)
* [网络、模版与网页应用](15.0.md)
  * [tcp服务器](15.1.md)
  * [一个简单的web服务器](15.2.md)
  * [访问并读取页面数据](15.3.md)
  * [写一个简单的网页应用](15.4.md)

## 第四部分：实际应用

* [常见的陷阱与错误](16.0.md)
  * [误用短声明导致变量覆盖](16.1.md)
  * [误用字符串](16.2.md)
  * [发生错误时使用defer关闭一个文件](16.3.md)
  * [何时使用new\(\)和make\(\)](16.4.md)
  * [不需要将一个指向切片的指针传递给函数](16.5.md)
  * [使用指针指向接口类型](16.6.md)
  * [使用值类型时误用指针](16.7.md)
  * [误用协程和通道](16.8.md)
  * [闭包和协程的使用](16.9.md)
  * [糟糕的错误处理](16.10.md)
* [模式](17.0.md)
  * [关于逗号ok模式](17.1.md)
* [出于性能考虑的实用代码片段](18.0.md)
  * [字符串](18.1.md)
  * [数组和切片](18.2.md)
  * [映射](18.3.md)
  * [结构体](18.4.md)
  * [接口](18.5.md)
  * [函数](18.6.md)
  * [文件](18.7.md)
  * [协程（goroutine）与通道（channel）](18.8.md)
  * [网络和网页应用](18.9.md)
  * [其他](18.10.md)
  * [出于性能考虑的最佳实践和建议](18.11.md)
* 第19章：构建一个完整的应用程序
* 第20章：Go 语言在 Google App Engine 的使用
* 第21章：实际部署案例

## 附录

* A 代码引用
* [B 有趣的 Go 引用](fu-lu/b-you-qu-de-go-yin-yong.md)
* C 代码示例列表
* D 书中的包引用
* E 书中的工具引用
* F 常见问题解答
* G 习题答案
* H 参考文献

## 索引

