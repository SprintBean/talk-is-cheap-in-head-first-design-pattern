# talk-is-cheap-in-head-first-design-pattern
## Talk is cheap,show me the code.

## 为什么建这个仓库

看了Head First系列,觉得话语太啰嗦了,看了本书提供的源码,感觉太简单了.但是提供的源码并没有很好的把类分成几个比较直观的包,所以我将这些书中的代码分成更加
直观的形式上传上来。

## 代码表达不出模式吗？
其实很多模式就是前人写的各种重复的代码中提取的经典用法,所以假如你没听过XX模式,那么先去查一查资料,这模式是干嘛的,等你知道为什么要使用该模式了,认真研究代码自然一目了然。思考代码为什么这么写,为什么某些地方要把变量提取出来,举个例子:比如为什么装饰模式中装饰类要有一个指向Component对象的引用。

### 学习设计模式的感受
有人拿设计模式的概念来装逼,比如依赖倒转,比如面向接口编程,但其实用代码来说明,可能就非常直观了.模式远远不止23种,各行各业都有模式,我们要尽可能多看一些优秀的直观的源码来了解模式,我想这是最简单粗暴的方法,看一下代码,就知道什么叫装饰,什么叫命令,什么叫策略了,当然有时候不止一种叫法。所以套用Linux那句话
> Talk is cheap,show me the code.

### 个人认为书中源码的弊端
这里的弊端不是指书中的源码不好,而是有时候作者写的代码会和作者的生活相挂钩(可以说是业务),作者是外国人,所以等我理解得更深刻了,会在作者提供的源码上进行一定的修改,修改成果然都理解的样子。

### 重复的力量
由于书中的代码有进行过一定的演变,所以在这个包中可能看到很多重复的代码,但是这些重复反而会加深我们的理解。

### 更多的模式
这本书提供的源码已经算不错了,但未能包括经典的23种模式源码,但模式远远不止23种,所以在未来希望提供更多的"模式"代码,但我想"模式"也不能全信,让时间去验证代码是否成功才是硬道理吧。
