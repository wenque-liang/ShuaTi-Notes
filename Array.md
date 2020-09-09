# 数组

什么是数组这点应该不用我多说了。

### 重要的方法：

1. 双指针法

双指针一般的应用如下：

1. 快慢指针；

快慢有两种：一种是一杯速两倍速，另一种是条件性快慢

2. 左右指针。


#11

如何在二维Array里面进行比较：
```
        Arrays.sort(intervals, new Comparator<int[]>() {
            @Override
            public int compare(int[] o1, int[] o2) {
                return o1[0]-o2[0];
            }
        });
```
