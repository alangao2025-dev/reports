# Google Ads 推广方案：美国 · 人工钻石（月预算 $1,000）

产品：lab grown diamond / 人工钻石 · 市场：US · 平台：Google Ads · run：20261103-us-lab-grown-diamond-2 · 渲染：2026-11-04T05:25:32Z

> 校验：数字 82/82 通过；未注出处 0，与证据不符 0，无效引用 0，规格错误 0，规格提醒 0。角标 [E..] 对应文末“引用证据”；[建议]/[假设] 为判断或假设值。

## 核心要点

| 维度 | 结论 |
|---|---|
| 平台角色 | 只做搜索收割：Google 搜索（服饰/时尚/珠宝 proxy）CVR 4.50% [E41]，CPC $4.44 [E37]；行业基准，非实测。 |
| 预算 | 月 $1,000、日 $32.89 [计算: CG2]，全部放进 1 个非品牌搜索系列，避免分散 [建议]。 |
| 结构 | 第一阶段 1 个系列 × 2 个广告组（耳钉、椭圆订婚戒），各 1 条写满的 RSA；Shopping 放第二阶段。 |
| 主推 | 耳钉 +190%、椭圆订婚戒 +350% [E4]，两个都是飙升方向；耳钉客单价约 $297.5 [E158]，用于先跑出转化。 |
| 效果预估 | 基准情景每月约 225 次点击、10 单，CPA $98.67 [计算: CG4,CG5,CG6]；保守情景（CVR 1.33%）仅 3 单、CPA $334 [计算: CGS5,CGS6]，高于盈亏平衡 CPA $149 [计算: CG9]。 |
| 关键门槛 | 第 4 周起以 CPA ≤ $149 [计算: CG9]（毛利率为假设值 [假设]）作为是否继续投放的硬门槛。 |

## 1. 平台定位、预算与 KPI

**为什么只投搜索**：$32.89/天 [计算: CG2] 在 CPC $4.44 [E37] 下每天只有约 7 次点击，撑不起 PMax 的学习和多系列测试。因此把全部预算集中在购买意图最强的非品牌搜索词上，地域先收窄到人造钻搜索领先的州 [建议]，依据 [E2,E6]。

**基准情景（Google 搜索 proxy 基准）**

| 指标 | 预估 |
|---|---|
| 平台月预算 | $1,000 [计算: CG1] |
| 平台日预算 | $32.89 [计算: CG2] |
| G1 预算 | $1,000/月（$32.89/天） [计算: CG3] |
| 预估点击 / 月 | 225 [计算: CG4] |
| 预估订单 / 月 | 10 [计算: CG5] |
| 预估 CPA | $98.67 [计算: CG6] |
| 预估销售额 / 月 | $3,015 [计算: CG7] |
| 预估 ROAS | 3.0x [计算: CG8] |
| 盈亏平衡 CPA（毛利 50% 假设） | $149 [计算: CG9] |

**保守情景（CVR 改用 Meta 珠宝下限 1.33%）**

| 指标 | 预估 |
|---|---|
| 预估点击 / 月 | 225 [计算: CGS4] |
| 预估订单 / 月 | 3 [计算: CGS5] |
| 预估 CPA | $334 [计算: CGS6] |
| 预估销售额 / 月 | $891 [计算: CGS7] |
| 预估 ROAS | 0.9x [计算: CGS8] |

> ⚠️ 以上是行业基准的量级预估，不是承诺。客单价按耳钉购物价中位 $297.5 [E158] 计；若订婚戒成交占比上升，客单价和盈亏平衡 CPA 都会明显提高。保守情景会亏损，所以第 1 个月的定位是「买数据」：验证哪类词能以 CPA ≤ $149 [计算: CG9] 成交。

## 2. 账户与追踪准备

**上线前必须完成**

- GA4 + Google Ads 转化标签：Purchase（主转化）、Add to cart、Begin checkout（次要转化，仅观察）
- 开启增强型转化（Enhanced Conversions），并回传订单金额，便于后续切换 tROAS
- 落地页按主报告第 6 章清单补齐：IGI 证书查询、免运费、退货政策、终身保修、关税已含说明（de minimis 已取消 [E144]）
- 建好两个落地页：/earrings/studs（耳钉合集）、/engagement-rings/oval（椭圆订婚戒合集），广告直达合集页，不落首页
- Merchant Center 开户并上传 Feed（第二阶段 Shopping 用），商品标题统一以「Lab-Grown Diamond」开头（FTC [E131]）
- GA4 建再营销受众（访客 30 天、加购未购），先积累，第二阶段使用

**文案规则**

- 每条广告必须包含其一：lab-grown, lab grown, lab-created, lab created
- 禁用词：investment, resale value, holds value, mined, natural diamond, real diamond, genuine diamond, eco-friendly, 100% sustainable, fake

## 3. 账户结构：广告系列 → 广告组 → 广告

| 广告系列 | 类型 / 目标 | 预算 | 广告组 | 广告数 |
|---|---|---|---|---|
| G1 US_Search_NonBrand_LabGrown | Search / Sales | $1,000/月（$32.89/天） [计算: CG3] | G1-1 Earrings_Studs<br>G1-2 EngagementRings_Oval | 2 |
| G2 US_Shopping_Earrings | Shopping / Sales | 第二阶段：G1 连续 4 周 CPA ≤ $149 [计算: CG9] 且月预算增加到 $1,500 以上 [建议] 时开启；从 G1 中拆出约 30% [建议]，不挤占搜索预算。 | G2-1 Shopping_Earrings_All | 1 |

### 广告系列 G1：US_Search_NonBrand_LabGrown

- 类型：Search　目标：Sales
- 预算：$1,000/月（$32.89/天） [计算: CG3]
- 出价：第 1–2 周 Maximize Clicks，CPC 上限设为基准 $4.44 [E37]；累计约 30 次转化 [建议] 后切 Maximize Conversions；再视 CPA 设 tCPA ≤ $149 [计算: CG9]。智能出价学习期最长 7 天 [E185]，切换后一周内不改设置。
- 排期：全天投放；第 2 周后按转化时段数据决定是否降低凌晨出价
- 为什么：Google 搜索承接高意向词，CVR 4.50%（proxy）[E41]；Rare Carat 在 Google 长期投放 2000 条广告，验证搜索渠道有效 [E168]。预算小，只开一个系列集中学习 [建议]。

| 项 | 设置 |
|---|---|
| 地区 | California、New York、New Jersey、Massachusetts、District of Columbia（人造钻搜索领先州 [E2]，DC 指数 16 [E6]）；第 2 个月视效果扩到全美 |
| 地区选项 | 所在地（Presence），不含「感兴趣」 |
| 语言 | English |
| 网络 | 仅 Google 搜索，关闭搜索网络合作伙伴和展示网络 |
| 广告组预算 | 两组共享系列预算；若耳钉组花费超过 70% 且无转化，再拆分 [建议] |

系列级否定关键词：`moissanite`, `cubic zirconia`, `cz`, `simulated`, `fake`, `cheap`, `free`, `wholesale`, `jobs`, `career`, `diy`, `how to make`, `used`, `rental`, `pawn`, `brilliant earth`, `kay`, `jared`, `zales`, `helzberg`

#### 广告组 G1-1：Earrings_Studs

- 为什么：耳钉 +190%、earrings 指数 27，话题 Lab Grown Diamond Earrings Breakout [E4,E5]；购物价中位 $297.5 [E158]，客单价低、决策快，最可能先跑出转化。

| 关键词 | 匹配 | 依据 |
|---|---|---|
| "lab grown diamond stud earrings" | phrase | rising +190% [E4] |
| "lab grown diamond studs" | phrase | rising 耳钉 +190% [E4] |
| "lab grown diamond earrings" | phrase | top 指数 27 [E4] |
| [lab diamond earrings] | exact | top 指数 27 [E4] |
| [lab grown diamond earrings] | exact | top 指数 27 [E4] |
| "lab created diamond earrings" | phrase | 同义词扩展 [建议] |
| "lab created diamond studs" | phrase | 同义词扩展 [建议] |
| "lab grown diamond stud earrings gold" | phrase | 话题 14k Breakout [E5] |
| "lab grown diamond hoop earrings" | phrase | 竞品在推 Pavé 圈形耳环 [E84] |
| "buy lab grown diamond earrings" | phrase | 购买意图词，SERP 有 rarecarat 广告 [E158] |
| "oval lab grown diamond studs" | phrase | 椭圆形状飙升 [E4] |

否定关键词：`ring`, `engagement`, `necklace`, `bracelet`, `men`, `piercing`

##### 广告 G1-1-A：RSA_Studs（rsa）

**headlines**（上限 30 字符）

1. Lab-Grown Diamond Studs　`23`
2. Lab-Grown Diamond Earrings　`26`
3. IGI Certified Lab-Grown　`23`
4. Everyday Sparkle Studs　`22`
5. Free Shipping & Returns　`23`
6. Gift-Ready Earrings　`19`
7. Lab-Grown Studs in Gold　`23`
8. Shop Lab-Grown Stud Earrings　`28`
9. Certificate With Every Pair　`27`
10. Lifetime Warranty Included　`26`
11. Classic Round & Oval Studs　`26`
12. Holiday Gifts She'll Love　`25`
13. Lab-Created Diamond Studs　`25`
14. Pay Later at Checkout　`21`
15. Shop Lab-Grown Earrings Now　`27`

**descriptions**（上限 90 字符）

1. Certified lab-grown diamond stud earrings in solid gold. Free shipping and easy returns.　`88`
2. Every pair ships with an IGI report you can verify online. Shop lab-grown studs today.　`86`
3. Everyday sparkle in a gift-ready box. Lab-grown diamonds backed by a lifetime warranty.　`87`
4. Round, oval and halo studs. Lab-grown diamonds, honestly priced. Order yours today.　`83`

**display_path**（上限 15 字符）

1. lab-grown　`9`
2. earrings　`8`

**callouts**（上限 25 字符）

1. Free Shipping　`13`
2. Easy Returns　`12`
3. IGI Certified Lab-Grown　`23`
4. Lifetime Warranty　`17`
5. Gift Box Included　`17`
6. Pay Later Available　`19`

**sitelinks**

| 文字 | 描述 1 | 描述 2 | URL |
|---|---|---|---|
| Lab-Grown Stud Earrings | Round and oval lab-grown studs | IGI certified, gift-ready | /earrings/studs |
| Lab-Grown Hoop Earrings | Pave hoops with lab-grown stones | Everyday sparkle in gold | /earrings/hoops |
| Verify Your Certificate | Look up any IGI report online | Every lab-grown stone is graded | /learn/igi-certificate |
| Lab-Grown vs Moissanite | How to tell them apart | Hardness, sparkle and testers | /learn/lab-grown-vs-moissanite |

落地页：/earrings/studs

**需商家确认的条款**：Free shipping；Easy returns；Lifetime warranty；Gift box included；Pay later (Klarna/Affirm)；IGI certificate with every pair；Solid gold settings

备注：IGI 主题搜索 +2,100% [E5]，证书放进标题和附加链接；莫桑石科普页用于应对 41 个州莫桑石领先的混淆 [E2]。

#### 广告组 G1-2：EngagementRings_Oval

- 为什么：椭圆订婚戒 +350%、engagement ring 指数 52 [E4]；椭圆款购物价中位 $1997 [E159]，客单价高，单笔成交即可覆盖较高 CPA。

| 关键词 | 匹配 | 依据 |
|---|---|---|
| "oval lab grown diamond engagement ring" | phrase | rising +350% [E4] |
| [oval lab grown engagement ring] | exact | rising +350% [E4] |
| "lab grown oval diamond ring" | phrase | 椭圆方向 +350% [E4] |
| [oval lab diamond ring] | exact | 椭圆方向 +350% [E4] |
| "lab grown diamond engagement ring" | phrase | top 指数 52、rising +170% [E4] |
| "lab grown engagement rings" | phrase | top 指数 52 [E4] |
| "lab created oval engagement ring" | phrase | 同义词扩展 [建议] |
| "1 carat oval lab grown diamond ring" | phrase | 1 carat +60% [E4] |
| "oval lab grown solitaire ring" | phrase | 竞品主推单钻 [E161] |
| "buy oval lab grown diamond ring" | phrase | 购买意图词 [建议] |

否定关键词：`earrings`, `studs`, `necklace`, `wedding band`, `men`, `promise ring`

##### 广告 G1-2-A：RSA_OvalRings（rsa）

**headlines**（上限 30 字符）

1. Oval Lab-Grown Diamond Ring　`27`
2. Lab-Grown Engagement Rings　`26`
3. Oval Lab-Grown Engagement　`25`
4. IGI Certified Lab-Grown　`23`
5. Design Your Own Ring　`20`
6. Ready-to-Ship Oval Rings　`24`
7. Free Resizing & Shipping　`24`
8. Lifetime Warranty Included　`26`
9. Lab-Created Diamond Rings　`25`
10. Certificate With Every Ring　`27`
11. Hand-Set in Solid Gold　`22`
12. Pay Over Time at Checkout　`25`
13. Shop Oval Lab-Grown Rings　`25`
14. Bigger Look, Smarter Budget　`27`
15. Lab-Grown Oval Solitaires　`25`

**descriptions**（上限 90 字符）

1. Oval lab-grown diamond engagement rings with IGI reports. Ready to ship or made to order.　`89`
2. Choose your lab-grown center stone, metal and setting. Free shipping and easy returns.　`86`
3. Every ring includes a lifetime warranty and free resizing. Lab-grown, certified, yours.　`87`
4. Same sparkle, smarter budget: certified lab-grown diamonds, honestly priced.　`76`

**display_path**（上限 15 字符）

1. engagement　`10`
2. oval　`4`

**callouts**（上限 25 字符）

1. Free Shipping　`13`
2. Free Resizing　`13`
3. IGI Certified Lab-Grown　`23`
4. Lifetime Warranty　`17`
5. Pay Over Time　`13`
6. Ready to Ship　`13`

**sitelinks**

| 文字 | 描述 1 | 描述 2 | URL |
|---|---|---|---|
| Oval Engagement Rings | Lab-grown oval center stones | Ready to ship or custom | /engagement-rings/oval |
| Design Your Ring | Pick a lab-grown stone | Then choose metal and setting | /design-your-ring |
| Verify Your Certificate | Look up any IGI report online | Every lab-grown stone is graded | /learn/igi-certificate |
| Lab-Grown vs Moissanite | How to tell them apart | Hardness, sparkle and testers | /learn/lab-grown-vs-moissanite |

落地页：/engagement-rings/oval

**需商家确认的条款**：Free shipping；Free resizing；Easy returns；Lifetime warranty；Pay over time (Klarna/Affirm)；Ready-to-ship oval rings in stock；Made-to-order option；Hand-set in solid gold；IGI certificate with every ring

备注：保障清单打法在 Meta 上已投放 694 天 [E51]，标题和附加信息沿用同一组保障；不写与天然钻的百分比对比，避免价格对比合规风险。

### 广告系列 G2：US_Shopping_Earrings

- 类型：Shopping　目标：Sales
- 预算：第二阶段：G1 连续 4 周 CPA ≤ $149 [计算: CG9] 且月预算增加到 $1,500 以上 [建议] 时开启；从 G1 中拆出约 30% [建议]，不挤占搜索预算。
- 出价：标准 Shopping，先 Manual CPC（起步出价低于搜索 CPC $4.44 [E37]），积累 30 次转化后改 Maximize Conversion Value [建议]。
- 为什么：耳钉购物结果中大卖场与 DTC 并存，价格中位 $297.5 [E158]；Shopping 卡片直接展示图片和价格，适合低客单价耳钉。Shopping 基准仅有 2018–19 年旧数据 [E38,E42]，需自测。

| 项 | 设置 |
|---|---|
| 地区 | 与 G1 一致 |
| 商品范围 | 仅耳钉品类（custom label = earrings） |
| 优先级 | Low（让精确词流量优先走 G1） |

系列级否定关键词：`moissanite`, `cubic zirconia`, `cz`, `simulated`, `fake`

#### 广告组 G2-1：Shopping_Earrings_All

- 为什么：按品类一个广告组起步，数据足够后再按价格档拆分 [建议]。

##### 广告 G2-1-A：Shopping_Feed_Earrings（shopping）

**descriptions**

1. Feed title format: Lab-Grown Diamond Stud Earrings, Round, Solid Gold, IGI Certified　`84`

落地页：/earrings/studs

备注：Feed 标题第一个词即为 Lab-Grown Diamond（FTC 要求标注靠近 diamond [E131]）；图片白底 + 一张佩戴图；product_type 填 Jewelry > Earrings > Lab-Grown Diamond Studs。

## 4. 测试与优化

**测试矩阵（一次只改一个变量）**

| 周次 | 变量 | 做法 | 判断标准 |
|---|---|---|---|
| 第 1–2 周 | 广告组：耳钉 vs 椭圆订婚戒 | 共享预算自然分配，不干预 | 看点击率、加购率，以及哪组先出转化 |
| 第 3–4 周 | RSA 标题主张：保障清单 vs 证书 | 固定 2–3 条保障标题 / 证书标题（Pin 到位置 1）做对比 | 广告级 CTR 与转化率 |
| 第 5–8 周 | 匹配方式 | 表现好的 phrase 词加 exact；搜索词报告中新词加入或否定 | CPA ≤ $149 [计算: CG9] |
| 第 2 个月 | 地域 | 从 5 个州扩到全美，或保留表现最好的州 | 扩量后 CPA 不高于原地域 20% [建议] |

**加减预算与关停规则**

- 每周一查搜索词报告，把 moissanite、CZ、竞品品牌和无关词加入否定
- 单个关键词花费达到 $149 [计算: CG9] 仍无转化 → 暂停
- 某组 2 周 CTR 低于搜索基准 6.64% [E32] 的一半 → 重写标题
- 整体连续 4 周 CPA > $149 [计算: CG9] → 停止加预算，先改落地页和价格，不靠加钱硬推
- CPA 稳定低于 $98.67 [计算: CG6] → 预算可以每周加 20% [建议]，并准备开启 G2

## 5. 上线排期

| 时间 | 重点 | 动作 |
|---|---|---|
| 上线前 1 周 | 追踪与落地页 | 转化标签、增强型转化、两个合集页、IGI 查询页、莫桑石对比页 |
| 第 1–2 周（11 月中下旬） | 上线测试 | G1 Maximize Clicks；黑五前后搜索与送礼需求上升，11 月预算占全年 9% [计算: CB1]；耳钉文案突出礼品 |
| 第 3–6 周（12 月） | 优化 | 12 月是成交节点（全年占比 11% [计算: CB1]）；按搜索词报告加否定，文案提示物流截止日 |
| 第 2–3 月（1 月起） | 复盘与调整 | 1 月为淡季（4% [计算: CB1]），可维持或下调预算；转化积累足够（约 30 次 [建议]）后切 Maximize Conversions；达标后开 G2 |

> 4–5 月是全年搜索峰值（4 月占 18%、5 月占 17% [计算: CB1]），若首季跑通，建议在 3 月底前把预算和椭圆订婚戒组准备好 [建议]。

## 6. 风险与审核

**审核与合规**

- FTC 珠宝指南：每条出现 diamond 的标题/描述都要带 lab-grown 或 lab-created，RSA 会随机组合，必须逐条标注 [E131]
- 不写 investment、holds value、natural、real、mined 等误导用语；批发价持续下跌，2025 年同比 -26% [E115]
- 不投竞品品牌词（Brilliant Earth、Kay 等），避免商标投诉；已加入否定
- Free shipping、退货、保修、Pay later 等条款上线前必须与网站政策一致，否则会被 Google 以「目的地不符」拒登
- 关税：de minimis 已取消 [E144]，落地页需说明是否含税，避免到货补税引发投诉和拒付

## 附录 A：计算说明

| 编号 | 说明 | 公式 | 结果 |
|---|---|---|---|
| CB1 | 全年预算的月度分配（引自主报告） | 见主报告 CB1 | 1 月 4%、2 月 8%、3 月 6%、4 月 18%、5 月 17%、6 月 10%、7 月 4%、8 月 4%、9 月 5%、10 月 4%、11 月 9%、12 月 11% |
| CG1 | google 月预算 | 总预算 1000 × 100% | $1,000 |
| CG2 | google 日预算 | 1,000.00 ÷ 30.4 | $32.89 |
| CG3 | 广告系列 G1 预算 | 1,000.00 × 100%，日 = 月 ÷ 30.4 | $1,000/月（$32.89/天） |
| CG4 | 月点击数（按 CPC） | 1,000.00 ÷ CPC 4.44 | 225 |
| CG5 | 月订单数 | 点击 × CVR 4.50% | 10 |
| CG6 | CPA | 1,000.00 ÷ 订单数 | $98.67 |
| CG7 | 月销售额 | 订单 × 客单价 297.5 | $3,015 |
| CG8 | ROAS | 销售额 ÷ 月预算 | 3.0x |
| CG9 | 盈亏平衡 CPA | 客单价 297.5 × 毛利率 50%（假设，可替换） | $149 |
| CGS4 | 保守情景：月点击数（按 CPC） | 1,000.00 ÷ CPC 4.44 | 225 |
| CGS5 | 保守情景：月订单数 | 点击 × CVR 1.33%（Meta 珠宝 CVR 下限，作保守替代） | 3 |
| CGS6 | 保守情景：CPA | 1,000.00 ÷ 订单数 | $334 |
| CGS7 | 保守情景：月销售额 | 订单 × 客单价 297.5 | $891 |
| CGS8 | 保守情景：ROAS | 销售额 ÷ 月预算 | 0.9x |

## 附录 B：数据缺失与假设

- 没有 Keyword Planner 的真实搜索量和 CPC，CPC/CVR 均为服饰/时尚/珠宝 proxy 基准 [E37,E41]
- 毛利率 50% 为假设，盈亏平衡 CPA 需按实际毛利重算
- 客单价按耳钉购物价中位计；订婚戒成交后整体客单价会更高
- 品牌名、网站域名、上线日期未提供；落地页路径为占位
- 未设品牌词系列：新品牌暂无品牌搜索，有品牌搜索后再加

## 附录 C：引用证据

- **E2** US 各州搜索领先词（today 12-m，共 51 个地区）：moissanite 领先 41 个（80.4%）；lab grown diamond 领先 10 个（19.6%） — [trends.google.com](https://trends.google.com/trends/explore?q=lab+grown+diamond%2Cmoissanite%2Ccubic+zirconia&geo=US&date=today+12-m) · 2026-11-04T05:12:19Z
- **E4** US 'lab grown diamond' 相关查询（today 12-m）飙升前列：apple iphone 17 pro max Breakout，lab grown yellow diamond +400%，oval lab grown diamond engagement ring +350%，lab grown pink diamond +250%，pink diamond +200%；热门前列：diamond ring 100，lab grown diamond ring 100，engagement ring 52，lab grown diamond engagement ring 52，lab diamond earrings 27 — [trends.google.com](https://trends.google.com/trends/explore?q=lab+grown+diamond&geo=US&date=today+12-m) · 2026-11-04T05:12:19Z
- **E5** US 'lab grown diamond' 相关主题（today 12-m）飙升前列：Lab Grown Diamond Earrings Breakout，14k Breakout，IGI +2,100%；热门前列：Diamond 100，Synthetic diamond 80，Ring 42，Carat 32，Engagement ring 24 — [trends.google.com](https://trends.google.com/trends/explore?q=lab+grown+diamond&geo=US&date=today+12-m) · 2026-11-04T05:12:19Z
- **E6** US 'lab grown diamond' 热度前 10 地区（today 12-m）：Wyoming 100，District of Columbia 16，Florida 15，Delaware 15，New York 15，California 15，New Jersey 14，Kansas 13，Arizona 13，Maryland 13 — [trends.google.com](https://trends.google.com/trends/explore?q=lab+grown+diamond&geo=US&date=today+12-m) · 2026-11-04T05:12:19Z
- **E32** US google_search CTR 行业基准（apparel_fashion_jewelry(proxy)，proxy，非实测）：6.64%（2025-04~2026-03），来源 WordStream by LocaliQ Google Ads Benchmarks 2026 — [wordstream.com](https://www.wordstream.com/blog/2026-google-ads-benchmarks) · 2026-11-04T05:12:28Z
- **E37** US google_search CPC 行业基准（apparel_fashion_jewelry(proxy)，proxy，非实测）：$4.44（2025-04~2026-03），来源 WordStream by LocaliQ Google Ads Benchmarks 2026 — [wordstream.com](https://www.wordstream.com/blog/2026-google-ads-benchmarks) · 2026-11-04T05:12:28Z
- **E38** US google_shopping CPC 行业基准（clothing_apparel(proxy)，proxy，非实测，数据较旧）：$0.69（2018-08~2019-02），来源 WordStream Google Shopping Ads Benchmarks — [wordstream.com](https://www.wordstream.com/blog/ws/2019/04/01/shopping-ads-benchmarks) · 2026-11-04T05:12:28Z
- **E41** US google_search CVR 行业基准（apparel_fashion_jewelry(proxy)，proxy，非实测）：4.50%（2025-04~2026-03），来源 WordStream by LocaliQ Google Ads Benchmarks 2026 — [wordstream.com](https://www.wordstream.com/blog/2026-google-ads-benchmarks) · 2026-11-04T05:12:28Z
- **E42** US google_shopping CVR 行业基准（clothing_apparel(proxy)，proxy，非实测，数据较旧）：2.70%（2018-08~2019-02），来源 WordStream Google Shopping Ads Benchmarks — [wordstream.com](https://www.wordstream.com/blog/ws/2019/04/01/shopping-ads-benchmarks) · 2026-11-04T05:12:28Z
- **E51** Meta 广告主 L'amour Brilliance（关键词 'lab grown diamond'，US）：样本内 3 条广告，最早投放 2024-12-10（已投 694 天），主页粉丝 2353，形式 VIDEO×3，落地页 lamourbrilliance.com — [facebook.com](https://www.facebook.com/ads/library/?id=593751476464413) · 2026-11-04T05:12:35Z
- **E84** Meta 广告主 Renaissance Jewel（关键词 'lab diamond earrings'，US）：样本内 2 条广告，最早投放 2026-05-15（已投 173 天），主页粉丝 19942，形式 DPA×2，落地页 renaissancejewel.com — [facebook.com](https://www.facebook.com/ads/library/?id=2152683905515705) · 2026-11-04T05:12:50Z
- **E115** edahngolan.com：Lab-Grown Diamond Wholesale Prices Down 26% in 2025 — [edahngolan.com](https://www.edahngolan.com/lab-grown-diamond-wholesale-prices-2025) · 2026-11-04T05:13:30Z
- **E131** ftc.gov：The many facets of advertising diamonds with clarity | Federal Trade Commission — [ftc.gov](https://www.ftc.gov/business-guidance/blog/2019/05/many-facets-advertising-diamonds-clarity) · 2026-11-04T05:13:48Z
- **E144** china-fulfillment.com：US De Minimis Is Gone: The 2026 Survival Guide for Sellers Shipping from China — [china-fulfillment.com](https://www.china-fulfillment.com/us-de-minimis-ended-2026-china-sellers-guide.html) · 2026-11-04T05:14:11Z
- **E158** Google(us) 'lab grown diamond stud earrings'：自然结果 7 条、广告 2 条、购物 60 条；购物结果价格 60 个，P25 $191.25 / 中位数 $297.5 / P75 $577.5（最低 $49.99） — [google.com](https://www.google.com/search?q=lab+grown+diamond+stud+earrings&gl=us&hl=en) · 2026-11-04T05:14:42Z
- **E159** Google(us) 'oval lab grown diamond engagement ring'：自然结果 7 条、广告 0 条、购物 8 条；购物结果价格 8 个，P25 $1177.28 / 中位数 $1996.55 / P75 $3572.24（最低 $534.67） — [google.com](https://www.google.com/search?q=oval+lab+grown+diamond+engagement+ring&gl=us&hl=en) · 2026-11-04T05:14:42Z
- **E161** renaissancejewel.com 首页：Lab Grown Diamond Rings, Diamond Jewelry | Renaissance Jewel — [renaissancejewel.com](https://www.renaissancejewel.com/) · 2026-11-04T05:14:48Z
- **E168** rarecarat.com 在 Google 广告透明度中心（区域 2840）共 2000 条广告，样本格式 text×49, image×1，最早展示 2022-07-27，最近展示 2026-11-04 — [adstransparency.google.com](https://adstransparency.google.com/?region=US&domain=rarecarat.com) · 2026-11-04T05:16:08Z
- **E185** google 官方规格：智能出价“学习中”状态最长持续天数 = 7 days（"Learning status never lasts more than 7 days"；预算/目标/素材修改不会触发学习状态） — [support.google.com](https://support.google.com/google-ads/answer/13020501?hl=en) · 2026-11-04T05:22:25Z
