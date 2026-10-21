# icons

签到 / 查询插件图标库。所有图标 512×512 PNG，iOS 圆角。

## 引用

```
https://raw.githubusercontent.com/mosenwoek/icons/refs/heads/main/<文件名>.png
```

## 图标清单

| 文件 | 来源 | 说明 |
|---|---|---|
| PingMe.png | App Store 官方图 | 青蓝定位针 + 灰斜杠 |
| WeTalk.png | 官方品牌图 | 绿底白电话 + WeTalk 字样 |
| AgentRouter.png | 官方原图 | 黑底青粉双弧环白星 |
| youjiacx.png | 用户提供 | 蓝底「最新油价」 |
| HCNSEC.png | 生成版 | 深底橙菱形闪电 |
| BoxJS.png | 生成版 | 绿底白铃铛 |
| xiaohuanxiong.png | 官网 logo 反色 | 深蓝底白色浣熊面具 |
| v2_square.png | 自制 | BoxJS 订阅主图（篮球框 + MOSEN） |
| mosen.png | 用户提供（AI 绘制） | 斗破苍穹萧炎×MOSEN 彩色涂鸦字 |
| yulanview.png | 用户提供（AI 绘制） | 预览插件（红蓝笔刷底 + 气球） |

## 使用

Loon 插件 / BoxJS 订阅里直接引用 URL：

```ini
img_url=https://raw.githubusercontent.com/mosenwoek/icons/refs/heads/main/youjiacx.png
```

## 工具链

| 工具 | 用途 |
|---|---|
| `appstore_icon.py` | iTunes Search API 抓 App Store 官方图 |
| `site_icon.py` | 抓网站 logo（真浏览器过 WAF/CF） |
| `lige_lookup.py` | lige 图标库检索（998 个知名 App） |
| `gen_icons_v2.py` | 生成式兜底（bell / compass / spark） |
| `icons_upload.py` | 批量上传到本仓库 |

## 加新图标

1. 拿到图（App Store / 网站 / 自制）
2. PIL 裁方 → 512×512 → 22% 圆角 → PNG
3. 存成 `<名字>.png` 放本目录
4. `python3 icons_upload.py <名字>.png`
