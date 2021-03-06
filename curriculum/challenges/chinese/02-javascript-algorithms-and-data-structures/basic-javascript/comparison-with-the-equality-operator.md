---
id: 56533eb9ac21ba0edf2244d0
title: 相等运算符
challengeType: 1
videoUrl: 'https://scrimba.com/c/cKyVMAL'
forumTopicId: 16784
---

# --description--

在 JavaScript 中，有很多<dfn>相互比较的操作</dfn>。所有这些操作符都返回一个`true`或`false`值。

最基本的运算符是相等运算符：`==`。相等运算符比较两个值，如果它们是同等，返回`true`，如果它们不等，返回`false`。值得注意的是相等运算符不同于赋值运算符（`=`），赋值运算符是把等号右边的值赋给左边的变量。

```js
function equalityTest(myVal) {
  if (myVal == 10) {
     return "Equal";
  }
  return "Not Equal";
}
```

如果`myVal`等于`10`，相等运算符会返回`true`，因此大括号里面的代码会被执行，函数将返回`"Equal"`。否则，函数返回`"Not Equal"`。 在 JavaScript 中，为了让两个不同的`数据类型`（例如`数字`和`字符串`）的值可以作比较，它必须把一种类型转换为另一种类型。然而一旦这样做，它可以像下面这样来比较：

```js
1   ==  1   // true
1   ==  2   // false
1   == '1'  // true
"3" ==  3   // true
```

# --instructions--

把`相等运算符`添加到指定的行，这样当`val`的值为`12`的时候，函数会返回"Equal"。

# --hints--

`testEqual(10)`应该返回 "Not Equal"。

```js
assert(testEqual(10) === 'Not Equal');
```

`testEqual(12)`应该返回 "Equal"。

```js
assert(testEqual(12) === 'Equal');
```

`testEqual("12")`应该返回 "Equal"。

```js
assert(testEqual('12') === 'Equal');
```

你应该使用`==`运算符。

```js
assert(code.match(/==/g) && !code.match(/===/g));
```

# --solutions--

