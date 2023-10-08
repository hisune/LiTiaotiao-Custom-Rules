# com.baidu.BaiduMap（百度地图）

## 基础规则

快速复制:
```
{"popup_rules":
    [
        {"id":"cancel_update","action":"cancel_update"},
        {"id":"yellow_banner_close","action":"yellow_banner_close"},
        {"id":"close_btn","action":"close_btn"},
        {"id":"operational_activities_content_close","action":"operational_activities_content_close"}
    ]
}
```

详细说明：
- [{"id":"cancel_update","action":"cancel_update"}](#idcancel_updateactioncancel_update)
- [{"id":"yellow_banner_close","action":"yellow_banner_close"}](#idyellow_banner_closeactionyellow_banner_close)
- [{"id":"close_btn","action":"close_btn"}](#idclose_btnactionclose_btn)
- [{"id":"operational_activities_content_close","action":"operational_activities_content_close"}](#idoperational_activities_content_closeactionoperational_activities_content_close)

### {"id":"cancel_update","action":"cancel_update"}
去除更新提示。

### {"id":"yellow_banner_close","action":"yellow_banner_close"}
去除首页黄页广告。

![](./assets/yellow_banner_close.jpg)

### {"id":"close_btn","action":"close_btn"}
去除打车界面右侧悬浮广告。

![](./assets/close_btn.jpg)

### {"id":"operational_activities_content_close","action":"operational_activities_content_close"}
去除打车界面弹出广告。

![](./assets/operational_activities_content_close.jpg)

## 增强规则