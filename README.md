# 日本二手房市场 — 2大网站跨站比价（SUUMO+at home 中古公寓）

**日本最大级不动产门户SUUMO与at home的东京23区中古公寓（二手房）售价跨站比较。相同车站·相同户型的房价一目了然。**

> 🇯🇵 English版: [Japan Property Market](https://apify.com/fruitful_quintessence)

## 输入

| 字段 | 类型 | 默认值 | 说明 |
|---|---|---|---|
| `ward` | select | `渋谷区` | 东京23区（千代田区/港区/新宿区/渋谷区/世田谷区等） |
| `maxItems` | integer | 100 | 最大获取件数 |
| `maxPages` | integer | 2 | 每个来源的最大页数 |
| `sources` | string | `suumo,athome` | 数据来源 |

## 输出示例

```json
{
  "productId": "suumo-sale-渋谷区-メゾンジャルダン-ワンルーム-0",
  "title": "メゾンジャルダン",
  "price": 29800000,
  "address": "東京都渋谷区千駄ヶ谷３-8-4",
  "station": "東京メトロ副都心線「北参道」徒歩5分",
  "layout": "ワンルーム",
  "areaSqm": "28.78m²",
  "source": "suumo_sale",
  "shop": "SUUMO 中古マンション",
  "ward": "渋谷区"
}
```

## 使用场景

- **投资分析**: 东京23区公寓价格走势追踪
- **跨网站比较**: 发现同一房产在不同网站的价格差
- **购房规划**: 移居日本前掌握房价行情

## 价格

按次计费 — $0.00005/次运行 + **$0.002/条**。
