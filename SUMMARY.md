# Summary

- [简介](README.md)
- [前言](eBook/preface.md)
- 第1章：[Go的起源、背景和流行度](ebook/01.1.md)
  - 01.1 [起源与发展](ebook/01.1.md)
  - 01.2 [语言的主要特性与发展的环境和影响因素](ebook/01.2.md)
- 第2章：[安装与运行时环境](ebook/02.1.md)
  - 02.1 [平台与架构](ebook/02.1.md)
  - 02.2 [Go 环境变量](ebook/02.2.md)
  - 02.3 [在 Linux 上安装 Go](ebook/02.3.md)
  - 02.4 [在 Mac OS X 上安装 Go](ebook/02.4.md)
  - 02.5 [在 Windows 上安装 Go](ebook/02.5.md)
  - 02.6 [安装目录清单](ebook/02.6.md)
  - 02.7 [Go 运行时（runtime）](ebook/02.7.md)
  - 02.8 [Go 解释器](ebook/02.8.md)
- 第3章：[编辑器、集成开发环境与其它工具](ebook/03.0.md)
  - 03.1 [Go 开发环境的基本要求](ebook/03.1.md)
  - 03.2 [编辑器和集成开发环境](ebook/03.2.md)
  - 03.3 [调试器](ebook/03.3.md)
  - 03.4 [构建并运行 Go 程序](ebook/03.4.md)
  - 03.5 [格式化代码](ebook/03.5.md)
  - 03.6 [生成代码文档](ebook/03.6.md)
  - 03.7 [其它工具](ebook/03.7.md)
  - 03.8 [Go 性能说明](ebook/03.8.md)
  - 03.9 [与其它语言进行交互](ebook/03.9.md)
- 第4章：[基本控制结构与数据类型](ebook/04.1.md)
  - 04.1 [文件名、关键字与标识符](ebook/04.1.md)
  - 04.2 [Go 程序的基本结构和要素](ebook/04.2.md)
  - 04.3 [常量](ebook/04.3.md)
  - 04.4 [变量](ebook/04.4.md)
  - 04.5 [基本类型和运算符](ebook/04.5.md)
  - 04.6 [字符串](ebook/04.6.md)
  - 04.7 [strings 和 strconv 包](ebook/04.7.md)
  - 04.8 [时间和日期](ebook/04.8.md)
  - 04.9 [指针](ebook/04.9.md)
- 第5章：[控制结构](ebook/05.0.md)
  - 05.1 [if-else 结构](ebook/05.1.md)
  - 05.2 [测试多返回值函数的错误](ebook/05.2.md)
  - 05.3 [switch 结构](ebook/05.3.md)
  - 05.4 [for 结构](ebook/05.4.md)
  - 05.5 [Break 与 continue](ebook/05.5.md)
  - 05.6 [标签与 goto](ebook/05.6.md)
- 第6章：[函数（function）](ebook/06.0.md)
  - 06.1 [介绍](ebook/06.1.md)
  - 06.2 [函数参数与返回值](ebook/06.2.md)
  - 06.3 [传递变长参数](ebook/06.3.md)
  - 06.4 [defer 和追踪](ebook/06.4.md)
  - 06.5 [内置函数](ebook/06.5.md)
  - 06.6 [递归函数](ebook/06.6.md)
  - 06.7 [将函数作为参数](ebook/06.7.md)
  - 06.8 [闭包](ebook/06.8.md)
  - 06.9 [应用闭包：将函数作为返回值](ebook/06.9.md)
  - 06.10 [使用闭包调试](ebook/06.10.md)
  - 06.11 [计算函数执行时间](ebook/06.11.md)
  - 06.12 [通过内存缓存来提升性能](ebook/06.12.md)
- 第7章：[数组与切片](ebook/07.0.md)
  - 07.1 [声明和初始化](ebook/07.1.md)
  - 07.2 [切片](ebook/07.2.md)
  - 07.3 [For-range 结构](ebook/07.3.md)
  - 07.4 [切片重组（reslice）](ebook/07.4.md)
  - 07.5 [切片的复制与追加](ebook/07.5.md)
  - 07.6 [字符串、数组和切片的应用](ebook/07.6.md)
- 第8章：[Map](ebook/08.0.md)
  - 08.1 [声明、初始化和 make](ebook/08.1.md)
  - 08.2 [测试键值对是否存在及删除元素](ebook/08.2.md)
  - 08.3 [for-range 的配套用法](ebook/08.3.md)
  - 08.4 [map 类型的切片](ebook/08.4.md)
  - 08.5 [map 的排序](ebook/08.5.md)
  - 08.6 [将 map 的键值对调](ebook/08.6.md)
- 第9章：[包（package）](ebook/09.0.md)
  - 09.1 [标准库概述](ebook/09.1.md)
  - 09.2 [regexp 包](ebook/09.2.md)
  - 09.3 [锁和 sync 包](ebook/09.3.md)
  - 09.4 [精密计算和 big 包](ebook/09.4.md)
  - 09.5 [自定义包和可见性](ebook/09.5.md)
  - 09.6 [为自定义包使用 godoc](ebook/09.6.md)
  - 09.7 [使用 go install 安装自定义包](ebook/09.7.md)
  - 09.8 [自定义包的目录结构、go install 和 go test](ebook/09.8.md)
  - 09.9 [通过 Git 打包和安装](ebook/09.9.md)
  - 09.10 [Go 的外部包和项目](ebook/09.10.md)
  - 09.11 [在 Go 程序中使用外部库](ebook/09.11.md)
- 第10章：[结构（struct）与方法（method）](ebook/10.0.md)
  - 10.1 [结构体定义](ebook/10.1.md)
  - 10.2 [使用工厂方法创建结构体实例](ebook/10.2.md)
  - 10.3 [使用自定义包中的结构体](ebook/10.3.md)
  - 10.4 [带标签的结构体](ebook/10.4.md)
  - 10.5 [匿名字段和内嵌结构体](ebook/10.5.md)
  - 10.6 [方法](ebook/10.6.md)
  - 10.7 [类型的 String() 方法和格式化描述符](ebook/10.7.md)
  - 10.8 [垃圾回收和 SetFinalizer](ebook/10.8.md)
- 第11章：[接口（interface）与反射（reflection）](ebook/11.0.md)
  - 11.1 [接口是什么](ebook/11.1.md)
  - 11.2 [接口嵌套接口](ebook/11.2.md)
  - 11.3 [类型断言：如何检测和转换接口变量的类型](ebook/11.3.md)
  - 11.4 [类型判断：type-switch](ebook/11.4.md)
  - 11.5 [测试一个值是否实现了某个接口](ebook/11.5.md)
  - 11.6 [使用方法集与接口](ebook/11.6.md)
  - 11.7 [第一个例子：使用 Sorter 接口排序](ebook/11.7.md)
  - 11.8 [第二个例子：读和写](ebook/11.8.md)
  - 11.9 [空接口](ebook/11.9.md)
  - 11.10 [反射包](ebook/11.10.md)
  - 11.11 [Printf 和反射](ebook/11.11.md)
  - 11.12 [接口与动态类型](ebook/11.12.md)
  - 11.13 [总结：Go 中的面向对象](ebook/11.13.md)
  - 11.14 [结构体、集合和高阶函数](ebook/11.14.md)
- 第12章：[读写数据](ebook/12.0.md)
  - 12.1 [读取用户的输入](ebook/12.1.md)
  - 12.2 [文件读写](ebook/12.2.md)
  - 12.3 [文件拷贝](ebook/12.3.md)
  - 12.4 [从命令行读取参数](ebook/12.4.md)
  - 12.5 [用 buffer 读取文件](ebook/12.5.md)
  - 12.6 [用切片读写文件](ebook/12.6.md)
  - 12.7 [用 defer 关闭文件](ebook/12.7.md)
  - 12.8 [使用接口的实际例子：fmt.Fprintf](ebook/12.8.md)
  - 12.9 [JSON 数据格式](ebook/12.9.md)
  - 12.10 [XML 数据格式](ebook/12.10.md)
  - 12.11 [用 Gob 传输数据](ebook/12.11.md)
  - 12.12 [Go 中的密码学](ebook/12.12.md)
- 第13章：[错误处理与测试](ebook/13.0.md)
  - 13.1 [错误处理](ebook/13.1.md)
  - 13.2 [运行时异常和 panic](ebook/13.2.md)
  - 13.3 [从 panic 中恢复（Recover）](ebook/13.3.md)
  - 13.4 [自定义包中的错误处理和 panicking](ebook/13.4.md)
  - 13.5 [一种用闭包处理错误的模式](ebook/13.5.md)
  - 13.6 [启动外部命令和程序](ebook/13.6.md)
  - 13.7 [Go 中的单元测试和基准测试](ebook/13.7.md)
  - 13.8 [测试的具体例子](ebook/13.8.md)
  - 13.9 [用（测试数据）表驱动测试](ebook/13.9.md)
  - 13.10 [性能调试：分析并优化 Go 程序](ebook/13.10.md)
- 第14章：[协程（goroutine）与通道（channel）](ebook/14.0.md)
  - 14.1 [并发、并行和协程](ebook/14.1.md)
  - 14.2 [协程间的信道](ebook/14.2.md)
  - 14.3 [协程的同步：关闭通道-测试阻塞的通道](ebook/14.3.md)
  - 14.4 [使用 select 切换协程](ebook/14.4.md)
  - 14.5 [通道、超时和计时器（Ticker）](ebook/14.5.md)
  - 14.6 [协程和恢复（recover）](ebook/14.6.md)
  - 14.7 [新旧模型对比：任务和worker](ebook/14.7.md)
  - 14.8 [惰性生成器的实现](ebook/14.8.md)
  - 14.9 [实现 Futures 模式](ebook/14.9.md)
  - 14.10 [复用](ebook/14.10.md)
  - 14.11 [限制同时处理的请求数](ebook/14.11.md)
  - 14.12 [链式协程](ebook/14.12.md)
  - 14.13 [在多核心上并行计算](ebook/14.13.md)
  - 14.14 [并行化大量数据的计算](ebook/14.14.md)
  - 14.15 [漏桶算法](ebook/14.15.md)
  - 14.16 [对Go协程进行基准测试](ebook/14.16.md)
  - 14.17 [使用通道并发访问对象](ebook/14.17.md)
- 第15章：[网络、模板与网页应用](ebook/15.0.md)
  - 15.1 [tcp 服务器](ebook/15.1.md)
  - 15.2 [一个简单的 web 服务器](ebook/15.2.md)
  - 15.3 [访问并读取页面数据](ebook/15.3.md)
  - 15.4 [写一个简单的网页应用](ebook/15.4.md)
  - 15.5 [确保网页应用健壮](ebook/15.5.md)
  - 15.6 [用模板编写网页应用](ebook/15.6.md)
  - 15.7 [探索 template 包](ebook/15.7.md)
  - 15.8 [精巧的多功能网页服务器](ebook/15.8.md)
  - 15.9 [用 rpc 实现远程过程调用](ebook/15.9.md)
  - 15.10 [基于网络的通道 netchan](ebook/15.10.md)
  - 15.11 [与 websocket 通信](ebook/15.11.md)
  - 15.12 [用 smtp 发送邮件](ebook/15.12.md)
- 第16章：[常见的陷阱与错误](ebook/16.0.md)
  - 16.1 [误用短声明导致变量覆盖](ebook/16.1.md)
  - 16.2 [误用字符串](ebook/16.2.md)
  - 16.3 [发生错误时使用 defer 关闭一个文件](ebook/16.3.md)
  - 16.4 [何时使用 new() 和 make()](ebook/16.4.md)
  - 16.5 [不需要将一个指向切片的指针传递给函数](ebook/16.5.md)
  - 16.6 [使用指针指向接口类型](ebook/16.6.md)
  - 16.7 [使用值类型时误用指针](ebook/16.7.md)
  - 16.8 [误用协程和通道](ebook/16.8.md)
  - 16.9 [闭包和协程的使用](ebook/16.9.md)
  - 16.10 [糟糕的错误处理](ebook/16.10.md)
- 第17章：[模式](ebook/17.0.md)
  - 17.1 [逗号 ok 模式](ebook/17.1.md)
  - 17.2 [defer 模式](ebook/17.2.md)
  - 17.3 [可见性模式](ebook/17.3.md)
  - 17.4 [运算符模式和接口](ebook/17.4.md)
- 第18章：[出于性能考虑的实用代码片段](ebook/18.0.md)
  - 18.1 [字符串](ebook/18.1.md)
  - 18.2 [数组和切片](ebook/18.2.md)
  - 18.3 [映射](ebook/18.3.md)
  - 18.4 [结构体](ebook/18.4.md)
  - 18.5 [接口](ebook/18.5.md)
  - 18.6 [函数](ebook/18.6.md)
  - 18.7 [文件](ebook/18.7.md)
  - 18.8 [协程（goroutine）与通道（channel）](ebook/18.8.md)
  - 18.9 [网络和网页应用](ebook/18.9.md)
  - 18.10 [其他](ebook/18.10.md)
  - 18.11 [出于性能考虑的最佳实践和建议](ebook/18.11.md)
- 第19章：[构建一个完整的应用程序](ebook/19.0.md)
  - 19.1 [简介](ebook/19.1.md)
  - 19.2 [短网址项目简介](ebook/19.2.md)
  - 19.3 [数据结构](ebook/19.3.md)
  - 19.4 [用户界面：web 服务端](ebook/19.4.md)
  - 19.5 [持久化存储：gob](ebook/19.5.md)
  - 19.6 [用协程优化性能](ebook/19.6.md)
  - 19.7 [以 json 格式存储](ebook/19.7.md)
  - 19.8 [多服务器处理架构](ebook/19.8.md)
  - 19.9 [使用代理缓存](ebook/19.9.md)
  - 19.10 [总结和增强](ebook/19.10.md)
