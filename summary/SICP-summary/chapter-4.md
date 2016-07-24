## 复合数据

题记：现在到了数学抽象中最关键的一步：让我们忘记这些符号所表示的对象。......（数学家）不应该在这里停步，有许多操作可以应用于这些符号，而根本不必考虑它们到底代表着什么东西。

————Hermann Weyl，数学的思维方式

### 第一节

高阶抽象是为了构建一个层次系统。因此构造的关键在于在构造东西的时候将构造整体的任务划分为实现部件的任务，其中心思想就是要建立层次化的系统，建立抽象屏障将细节隔离在底层，将细节与所工作的高层环境隔离开，底层的细节，底层的思想，都不重要。

编程的本质是：希望程序设计语言能够表达大脑中的概念

### 第二节

对复合数据而言，建立抽象层，准确地说，就是建立构造函数和选择函数，这种做法就是“分离”对象的使用方法。把数据对象的使用与其表示分离开来，这个分离便是由抽象层来实现的。这种方法也叫数据抽象

数据抽象：通过假定的构造函数和选择函数将数据对象与它的表示分隔开来的编程方法学

### 第三节

数据抽象技术是一种在大型系统中控制复杂度的方法，通过将数据不断地复合，并通过抽象层进行数据隔离，能够操作复杂的数据。

### 第四节

过程并不仅仅是动作的集合，过程是概念实体，是对象，过程不仅仅是说做某件事的行为，任何过程都是一个存在的真实对象