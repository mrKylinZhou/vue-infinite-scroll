## Change Log

### 0.0.8
  - 解决了初始加载是父级是display:node 导致wrapper层 获取高度为0
  - 解决了初始加载时由于没有达到滚动条件（wrapper 高度大于 滚动列表高度时）时组件报错问题

### 0.0.13
  - 新增wrapCustomClass
  - 新增rowCustomClass
  - 完善了README.md

### 0.0.14
  - 解决了lists变更时报错问题
  - 去掉了props中传递length,改为自动计算
  - Wrap传递的height改为最大高度,Wrap高度改为自动计算
  - 去掉了useIScroll判断,改为统一使用
  - 优化了组件卸载时IScroll实例没有被销毁

### 0.0.15
  - 修复了组件被嵌套在popover中显示不出来的问题

### 0.0.16
  - 修复了组件被嵌套在popover卡顿问题

### 0.0.19
  - 修复了某一次lists长度变更为0时报找不到offsetHeight问题
