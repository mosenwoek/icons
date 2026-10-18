# icons

签到插件图标库。所有图标 512×512 PNG，iOS 圆角。

## 引用

```
https://raw.githubusercontent.com/mosenwoek/icons/refs/heads/main/<文件名>.png
```

## 图标清单

| 文件 | 来源 | 说明 |
|---|---|---|
| PingMe.png | App Store 官方图 | 青蓝定位针 + 灰斜杠 |
| WeTalk.png | 官方品牌图 | 绿底白电话 + WeTalk 字样 |
| AgentRouter.png | 官方原图（ps.air-outer.com） | 黑底青粉双弧环白星 |
| HCNSEC.png | 生成版（v2 compass 风格） | 深底橙菱形闪电 |
| BoxJS.png | 生成版（v2 bell 风格） | 绿底白铃铛 |

## 使用

Loon 插件 / BoxJS 订阅里直接引用上面的 URL，例：

```ini
img_url=https://raw.githubusercontent.com/mosenwoek/icons/refs/heads/main/PingMe.png
```

## 工具链

- `appstore_icon.py` — iTunes Search API 抓 App Store 官方图
- `site_icon.py` — 抓网站 logo（真浏览器过 WAF/CF）
- `lige_lookup.py` — lige 图标库检索（998 个知名 App）
- `gen_icons_v2.py` — 生成式兜底（bell / compass / spark 三种构图）
