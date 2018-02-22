# 步骤一 配置相关信息
在WyConfig.php里面配置WY_APPKEY和WY_APPSCECRET。WY_REQUESTTYPE不修改
# 步骤二 调用接口 `详情接口说明请参考demoServerAPI.php`
```
//创建直播间
print_r(\WyLive\WyLiveApi::instance()->channelCreate('test_channel',1));
//也可以先在类文件顶部use后调用
use WyLive\WyLiveApi;
print_r(WyLiveApi::instance()->channelCreate('test_channel',1));
```

