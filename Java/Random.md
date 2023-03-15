# Random类

## 简介

Random类时Java中生成随机数的类
> 虽然Random类产生数字是随机的，但是相同的种子数(seed)下的相同次数产生的随机数是相同的

## 构造方法

1. Random()

    创建一个以系统自身的时间为种子数的随机数生成器。

2. Random​(long seed)

    创建一个指定种子数的随机数生成器。

## 常用方法

1. public int nextInt()

    随机生成一个int类型的整数

2. public int nextInt​(int bound)

    随机生成一个从0(包含)到bound(不包含)之间且为int类型的整数

3. public int nextInt(int origin, int bound)

    随机生成一个从origin(包含)到bound(不包含)之间且为int类型的整数
