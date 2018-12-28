# Decaf pa5 report

1. 连边条件

把所有的Def和tac里面的东西连起来就行了

2. 完整染色算法

修改InferenceGraph中的color函数即可，把后面的IllegalArgumentException换成如下代码：

```
chooseAvailableRegister(n);
return color();
```

经过测试能够通过。
