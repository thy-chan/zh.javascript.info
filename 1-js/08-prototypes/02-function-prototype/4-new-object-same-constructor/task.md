importance: 5

---

# 使用相同的构造函数创建一个对象

想象一下，我们有一个任意对象 `obj`，由一个构造函数创建 —— 我们不知道这个构造函数是什么，但是我们想用它创建一个新对象。

我们可以这样做吗？

```js
let obj2 = new obj.constructor();
```

给出一个代码可以正常工作的 `obj` 的构造函数的例子。再给出一个会导致错误的例子。