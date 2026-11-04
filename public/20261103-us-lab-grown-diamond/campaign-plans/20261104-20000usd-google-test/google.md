# Google Ads 推广方案（测试）

产品：lab grown diamond · 市场：US · 平台：Google Ads · run：t · 渲染：2026-11-03T13:28:34Z

> 校验：数字 6/8 通过；未注出处 1，与证据不符 1，无效引用 0，规格错误 1，规格提醒 0。角标 [E..] 对应文末“引用证据”；[建议]/[假设] 为判断或假设值。

## 核心要点

| 维度 | 结论 |
|---|---|
| 角色 | 收割高意图词，CVR 4.50% [E41] |
| 编造 | ROAS 可达 8 倍 |

## 1. 平台定位、预算与 KPI

| 项 | 值 |
|---|---|
| 月预算 | $10,000 [假设] |
| Google 占比 | 35% [建议] |

**文案规则**

- 每条广告必须包含其一：lab-grown, lab grown, lab-created
- 禁用词：investment, natural diamond

## 3. 账户结构：广告系列 → 广告组 → 广告

| 广告系列 | 类型 / 目标 | 预算 | 广告组 | 广告数 |
|---|---|---|---|---|
| G1 Search - Engagement Rings | Search / Sales | $80/天 [计算: C9] | G1-1 Oval | 1 |

### 广告系列 G1：Search - Engagement Rings

- 类型：Search　目标：Sales
- 预算：$80/天 [计算: C9]
- 出价：Max conversions
- 为什么：oval +350% [E4]

#### 广告组 G1-1：Oval


| 关键词 | 匹配 | 依据 |
|---|---|---|
| "oval lab grown diamond engagement ring" | phrase | +350% [E4] |

##### 广告 G1-1-A：RSA（rsa）

**headlines**

1. Oval Lab-Grown Engagement Rings　`31`
2. This headline is definitely way too long for google　`51`
3. IGI Certified Diamonds　`22`

**descriptions**

1. Shop oval lab-grown diamonds, 70% less than mined. Free shipping.　`65`
2. Great investment.　`17`

**display_path**

1. oval　`4`
2. rings　`5`

落地页：https://example.com/oval

**文案依据**：E84

**需商家确认的条款**：Free shipping

## 附录 A：计算说明

| 编号 | 说明 | 公式 | 结果 |
|---|---|---|---|
| C9 | 日预算 | 10000*35%/30≈117 |  |

## 附录 C：引用证据

- **E4** US 'lab grown diamond' 相关查询（today 12-m）飙升前列：apple iphone 17 pro max Breakout，lab grown yellow diamond +400%，oval lab grown diamond engagement ring +350%，lab grown pink diamond +250%，pink diamond +200%；热门前列：diamond ring 100，lab grown diamond ring 100，engagement ring 52，lab grown diamond engagement ring 52，lab diamond earrings 27 — [trends.google.com](https://trends.google.com/trends/explore?q=lab+grown+diamond&geo=US&date=today+12-m) · 2026-11-03T12:29:26Z
- **E41** US google_search CVR 行业基准（apparel_fashion_jewelry(proxy)，proxy，非实测）：4.50%（2025-04~2026-03），来源 WordStream by LocaliQ Google Ads Benchmarks 2026 — [wordstream.com](https://www.wordstream.com/blog/2026-google-ads-benchmarks) · 2026-11-03T12:29:56Z
- **E84** cnbc.com：More couples are choosing lab-grown diamonds vs. natural for engagement rings — [cnbc.com](https://www.cnbc.com/2025/03/10/more-couples-are-choosing-lab-grown-diamonds-vs-natural-for-engagement-rings.html) · 2026-11-03T12:30:56Z

## 附录 D：校验问题

| 类型 | 内容 | 位置 | 说明 |
|---|---|---|---|
| 数字 | 8 倍 | summary[1].conclusion | ROAS 可达 8 倍 |
| 数字 | 70% | campaigns[0].ad_groups[0].ads[0].descriptions[0] | 文案数字在 substantiation 证据中找不到，且不在 merchant_terms |
| 规格-error | Great investment. | campaigns[0].ad_groups[0].ads[0].descriptions[1] | 出现禁用词 “investment” |
