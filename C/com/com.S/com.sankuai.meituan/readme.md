# com.sankuai.meituan（美团）

## 基础规则

快速复制:
```
{"popup_rules":
    [
        {"id":"update_title","action":"btn_close"},
        {"id":"bottom_center_close_button","action":"bottom_center_close_button"},
        {"id":"订单已满&优惠换购","action":"放弃机会"},
        {"id":"恭喜你获得以下权益","action":"GLOBAL_ACTION_BACK"},
        {"id":"popContentImg","action":"popCloseBtn"}
    ]
}
```
详细说明：
- [{"id":"update_title","action":"btn_close"}](#idupdate_titleactionbtn_close)
- [{"id":"bottom_center_close_button","action":"bottom_center_close_button"}](#idbottom_center_close_buttonactionbottom_center_close_button)
- [{"id":"订单已满&优惠换购","action":"放弃机会"}](#id订单已满优惠换购action放弃机会)
- [{"id":"恭喜你获得以下权益","action":"GLOBAL_ACTION_BACK"}](#id恭喜你获得以下权益actionglobal_action_back)
- [{"id":"popContentImg","action":"popCloseBtn"}](#idpopcontentimgactionpopclosebtn)

### {"id":"update_title","action":"btn_close"}
去除更新弹窗

![](./assets/更新弹窗.jpg)

### {"id":"bottom_center_close_button","action":"bottom_center_close_button"}
去除外卖页面红包弹窗

![](./assets/bottom_center_close_button.jpg)

### {"id":"订单已满&优惠换购","action":"放弃机会"}
去除提交订单后弹出的 “优惠换购” 弹窗

![](./assets/优惠换购.jpg)

### {"id":"恭喜你获得以下权益","action":"GLOBAL_ACTION_BACK"}
去除支付成功后弹出的 “领红包” 弹窗（⚡需要手动触发）

![](./assets/支付成功领红包.jpg)

### {"id":"popContentImg","action":"popCloseBtn"}
去除 “骑行” 页面福利红包弹窗

![](./assets/骑行页面福利红包弹窗.jpg)

## 增强规则
