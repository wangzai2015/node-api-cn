
默认的解释器会把最近一次解释的表达式的结果赋值给变量 `_` （下划线）。

```js
> [ 'a', 'b', 'c' ]
[ 'a', 'b', 'c' ]
> _.length
3
> _ += 1
4
```

显式地设置 `_` 为某个值能禁用该特性。

