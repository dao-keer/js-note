## 下面这篇文章总结了数组操作是否影响原数组的值

> https://zhuanlan.zhihu.com/p/69627217

最后的总结是：

- 改变原数组的有：pop, push, shift, unshift, reverse, sort, splice, 
- forEach如果通过数组的索引改变了值，则原数组会发生变化，如果没有则原数组不发生改变
