# 浮点精度

## 浮点精度问题

举例：商品原价 100，打 8.8 折。
```
100 * (8.8 / 10)
= 8.799999999999999
```

某些特定数据做四则运算：

```
0.1 + 0.2
= 0.30000000000000004

0.3 - 0.1
= 0.19999999999999998

```

## 处理浮点精度的方法

1. BigDecimal