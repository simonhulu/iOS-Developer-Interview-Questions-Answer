iOS-Developer-Interview-Questions-Answer
========================================

最近投了几份简历，有面试有笔试，深刻意识到自己的弱项——“轻理论”，所以希望通过这份文档来夯实自己在iOS开发中的理论基础

会列出一些知识点，并且会给出详细的解释，利人利己

这个东西还挺难写的......得慢慢来......

## 问题

- 当一个strong指针和一个weak指针指向同一个对象时，若strong指针释放了该对象，weak指针会变成什么？
	weak指针会被赋值为```nil```


## <a name="lists">知识点清单</a>

- [__weak修饰符和__strong修饰符](#weak_strong)
- [Objective-C中的Blocks](#blocks)
- [引用计数](#reference_count)
- [ARC](#ARC)
- ......

### <a name="weak_strong">__weak修饰符和__strong修饰符</a>

(待补充...)

### <a name="blocks">Objective-C中的Blocks</a>

(待补充...)

### <a name="reference_count">引用计数</a>

(待补充...)

### <a name="ARC">ARC</a>

ARC是“由编译器进行内存管理”，但只有编译器还不够，需要Objective-C运行时库的协助，所以ARC的实现需要：

- clang
- Objective-C运行时库

简单理解，ARC和垃圾回收不一样，ARC有效时，你不能使用```retain``` \ ```release``` \ ```retainCount``` \ ```autorelease```，但是实际上ARC在编译器自动加上这些语句

(待补充...)


## TODO

(待补充...)

## 参考资料

- 《Objective-C高级编程》；坂本一树 (Kazuki Sakamoto)、古本智彦 (Tomohiko Furumoto) 著；黎华 译；人民邮电出版社