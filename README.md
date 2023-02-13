# 创业选址
如果我们想创业开一个小店，比如火锅店或奶茶店，最重要的一步就是选择我们店铺的位置，选择店铺通常要考虑几个方面：
1. 什么位置周围的竞争最小？
2. 什么位置周围的客户最多？

本项目为想要解决这两个问题的用户提供了一个思路

## 示例
项目使用开奶茶店为例，假定火锅店附件消费奶茶的客户比较多，下面分几步完成奶茶店位置的选择
1. 用爬虫在网上拉取当前城市所有的奶茶店、火锅店，及其位置
2. 在地图上展示火锅店和奶茶店的位置，火锅店用热力图展示
3. 找出周围2km没有奶茶店的火锅店
4. 画出奶茶店,和附件没有奶茶店的火锅店的热力图
5. 计算客流量最大的奶茶店
6. 在地图上找到空白处最大的位置（没有奶茶店的位置），作为开店的位置
