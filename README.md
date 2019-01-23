# xbosstrack 小程序自动埋点
### 使用方法

1、App.js文件引入资源

```
// 引入埋点SDK
import Tracker from './xbosstrack.min.js';
// 引入埋点配置信息，请自行参考tracks目录下埋点配置修改
import trackConfig from './tracks/index';
```

2、初始化

```
new Tracker({ tracks: trackConfig });
```



### 方案实现说明

[小程序从手动埋点到自动埋点](https://github.com/zhengguorong/articles/issues/34)

[DEMO](https://github.com/zhengguorong/maizuo_wechat)

