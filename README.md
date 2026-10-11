# shadowrocket-rules
# Shadowrocket 分流规则

## hongguo-direct.list
让红果短剧 App 直连、不走代理的规则集。

### 使用方法
1. 小火箭 → 底部「配置」→ 点进正在用的配置文件 →「规则集」
2. 右上角 + → 粘贴订阅链接：
   https://raw.githubusercontent.com/HelloiMolly/shadowrocket-rules/main/hongguo-direct.list
3. 确保该规则集排在 `MATCH` 兜底规则之前
4. 断开重连一次 VPN

### 验证
小火箭日志里红果相关域名的 `result` 应显示为 `ROUTING,DIRECT`。
