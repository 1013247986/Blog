##相同点

* 一、Vue.js(2.0版本)与React的其中最大一个相似之处，就是他们都使用了一种叫'Virtual DOM'的东西。所谓的Virtual DOM基本上说就是它名字的意思：虚拟DOM，DOM树的虚拟表现。它的诞生是基于这么一个概念：改变真实的DOM状态远比改变一个JavaScript对象的花销要大得多

* 二、Virtual DOM是一个映射真实DOM的JavaScript对象，如果需要改变任何元素的状态，那么是先在Virtual DOM上进行改变，而不是直接改变真实的DOM。当有变化产生时，一个新的Virtual DOM对象会被创建并计算新旧Virtual DOM之间的差别。之后这些差别会应用在真实的DOM上。

## 不同点



####一、数据

* vue是数据双向绑定   react是单向数据流