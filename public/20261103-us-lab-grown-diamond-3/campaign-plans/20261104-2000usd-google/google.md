# Google Ads 推广方案：美国 · 人造钻石（月预算 $2,000）

产品：lab grown diamond / 人造钻石 · 市场：US · 平台：Google Ads · run：20261103-us-lab-grown-diamond-3 · 渲染：2026-11-04T08:09:09Z

> 校验：数字 119/119 通过；未注出处 0，与证据不符 0，无效引用 0，规格错误 0，规格提醒 0。角标 [E..] 对应文末“引用证据”；[建议]/[假设] 为判断或假设值。

## 核心要点

| 维度 | 结论 |
|---|---|
| 平台角色 | Google 是唯一投放平台，专门收割购买意图明确的搜索；行业基准 CVR 4.50% [E40]，CPC $4.44 [E36]（proxy 品类，非实测） |
| 预算 | 月 $2,000、日 $65.79 [计算: CG2]；搜索非品牌词 $1,300/月（$42.76/天）[计算: CG3]，购物广告 $700/月（$23.03/天）[计算: CG4] |
| 结构 | 第一阶段 2 个广告系列、4 个广告组：椭圆订婚戒、培育钻订婚戒通用词、LGD 耳钉 + 标准购物广告；彩钻搜索放第二阶段 |
| 预估 | 约 450 次点击/月 [计算: CG5]；保守情景订单 13 [计算: CGC6]、CPA $160 [计算: CGC7]；基准情景订单 20 [计算: CG6]、CPA $98.67 [计算: CG7] |
| 考核门槛 | CPA ≤ 盈亏平衡 CPA $494 [计算: CG10]（按毛利率 50% [假设] 计算，可替换）；ROAS 预估 10.0x [计算: CG9] 明显偏高，不作为考核 |
| 核心打法 | 主推椭圆款（+350% [E4]），文案突出 IGI 证书 + 诚实定价 + 终身保修，每条都带 lab-grown 限定词（FTC [E114]） |

## 1. 平台定位、预算与 KPI

预算只有 $2,000/月 [计算: CG1]，按 CPC $4.44 [E36] 算，一个月只有约 450 次点击 [计算: CG5]。所以只开 2 个系列，把点击集中在需求最强的订婚戒和增速最快的耳钉上；品牌词、彩钻、PMax、YouTube 都放到数据跑通之后。

**预算与 KPI 预估（基准情景，CVR 4.50% proxy）**

| 指标 | 预估 |
|---|---|
| 平台月预算 | $2,000 [计算: CG1] |
| 平台日预算 | $65.79 [计算: CG2] |
| G1 搜索非品牌词 | $1,300/月（$42.76/天） [计算: CG3] |
| G2 标准购物广告 | $700/月（$23.03/天） [计算: CG4] |
| 预估点击 / 月 | 450 [计算: CG5] |
| 预估订单 / 月 | 20 [计算: CG6] |
| 预估 CPA | $98.67 [计算: CG7] |
| 预估销售额 / 月 | $20,047 [计算: CG8] |
| 预估 ROAS | 10.0x [计算: CG9] |
| 盈亏平衡 CPA | $494 [计算: CG10] |

**保守情景（CVR 2.78%，服饰配件 proxy [E42]）**

| 指标 | 预估 |
|---|---|
| 预估点击 / 月 | 450 [计算: CGC5] |
| 预估订单 / 月 | 13 [计算: CGC6] |
| 预估 CPA | $160 [计算: CGC7] |
| 预估销售额 / 月 | $12,385 [计算: CGC8] |
| 预估 ROAS | 6.2x [计算: CGC9] |

> ⚠️ 预估都来自行业基准（proxy 品类），不是承诺。客单价用竞品成品戒指中位数 $989 [E143]；订婚戒的高客单、长决策周期会让真实 CVR 明显低于基准，首月请用加购成本和 CPA 判断，不用 ROAS。

## 2. 账户与追踪准备

**转化与追踪**

- GA4 + Google Ads 转化标签：Purchase（主要转化，传订单金额）、Begin checkout、Add to cart（次要转化）
- 开启增强型转化（Enhanced Conversions），并按同意模式（Consent Mode）处理加州等地的隐私告知
- 订单少的阶段，把 Add to cart 设为次要转化观察，不参与出价

**Merchant Center 商品源**

- 商品标题统一以 “Lab-Grown Diamond” 开头，写清形状、克拉、金属，例如 Oval Lab-Grown Diamond Engagement Ring（FTC 要求标注 [E114]）
- 填写 GTIN 不适用时设 identifier_exists=no；product_type 按 订婚戒 / 耳钉 / 项链 分层，方便购物广告分组
- custom_label_0 标主推款（椭圆、耳钉），custom_label_1 标价格档
- 配置运费和退货政策，与落地页一致；页面写明含税、无额外进口费用（de minimis 已暂停 [E120]）

**受众列表（观察模式）**

- 网站访客 30 天 / 加购未购 30 天（RLSA 观察，不做定向）
- 客户邮件名单（Customer Match，有名单后再上传）
- 账户级否定：竞品品牌词、招聘、批发、DIY 等（见各系列否定词）

**文案规则**

- 每条广告必须包含其一：lab-grown, lab grown, lab-created, lab created
- 禁用词：investment, resale value, mined, natural diamond, real diamond, genuine diamond, moissanite, flawless

## 3. 账户结构：广告系列 → 广告组 → 广告

| 广告系列 | 类型 / 目标 | 预算 | 广告组 | 广告数 |
|---|---|---|---|---|
| G1 US_Search_NonBrand_LGD | Search / Sales | $1,300/月（$42.76/天） [计算: CG3] | G1-1 Oval Engagement Rings<br>G1-2 LGD Engagement Rings Generic<br>G1-3 LGD Stud Earrings | 3 |
| G2 US_Shopping_Standard_LGD | Shopping / Sales | $700/月（$23.03/天） [计算: CG4] | G2-1 Feed_Engagement_and_Studs | 1 |
| G3 US_Search_NonBrand_ColoredLGD | Search / Sales | 从 G1 调拨 $300/月左右 [建议]；开启条件：G1 连续 4 周 CPA ≤ $494 [计算: CG10]，且已上架黄钻/粉钻商品 | G3-1 Yellow and Pink LGD | 1 |

### 广告系列 G1：US_Search_NonBrand_LGD

- 类型：Search　目标：Sales
- 预算：$1,300/月（$42.76/天） [计算: CG3]
- 出价：前 2–4 周用 Maximize Clicks，CPC 上限 $6 [建议]（依据基准 CPC $4.44 [E36]）；累计约 15–20 个购买转化 [建议] 后切 Maximize Conversions，再稳定后设 tCPA，目标不高于盈亏平衡 CPA $494 [计算: CG10]
- 排期：全天投放；首月观察时段报表后再降低凌晨出价
- 为什么：搜索 CVR 4.50% [E40] 是三个平台里最高的，最适合收割“engagement ring / oval / studs”这类意图明确的词；订婚戒热门指数 52 [E4]，耳钉 +190% [E4]。

| 项 | 设置 |
|---|---|
| 地区 | 美国全国（按所在地，不按兴趣） |
| 语言 | English |
| 网络 | 仅搜索网络（关闭搜索网络合作伙伴和展示网络） |
| 设备 | 不限，观察移动端转化后再调整 |

系列级否定关键词：`moissanite`, `cubic zirconia`, `cz`, `fake`, `simulated`, `free`, `jobs`, `career`, `wholesale`, `diy`, `how to make`, `rental`, `used`, `pawn`, `resale`, `machine`, `industrial`, `mined`, `natural diamond`, `brilliant earth`, `blue nile`, `pandora`, `kay`, `zales`, `jared`, `helzberg`

#### 广告组 G1-1：Oval Engagement Rings

- 为什么：椭圆订婚戒是增速最高的订婚戒方向（+350% [E4]），主力利润款（报告第 5 章，优先级 5）

| 关键词 | 匹配 | 依据 |
|---|---|---|
| [oval lab grown diamond engagement ring] | exact | rising +350% [E4] |
| "oval lab grown diamond engagement ring" | phrase | rising +350% [E4] |
| "oval lab grown diamond ring" | phrase | 椭圆 +350% 的变体 [E4] |
| "oval lab diamond engagement ring" | phrase | lab diamond 是常见简称，lab diamond rings 指数 21 [E4] |
| "lab grown oval engagement ring" | phrase | 词序变体 [E4] |
| "oval lab created diamond ring" | phrase | lab created 是核心词之一 [推断] |
| "2 carat oval lab grown diamond ring" | phrase | lab grown 2 carat diamond 指数 15 [E4] |
| "1 carat oval lab grown diamond" | phrase | 1 carat lab grown diamond +60% [E4] |
| [oval lab grown diamond] | exact | 椭圆主题 [E4]；话题 Oval 指数 5 [E5] |
| "oval engagement ring lab grown" | phrase | 词序变体 [E4] |
| "igi certified oval lab grown diamond" | phrase | IGI 话题 +2,100% [E5] |

否定关键词：`earrings`, `studs`, `necklace`, `bracelet`, `loose`

##### 广告 G1-1-A：RSA_Oval_Certified_HonestPrice（rsa）

**headlines**（上限 30 字符）

1. Oval Lab-Grown Diamond Rings　`28`
2. IGI Certified Lab-Grown　`23`
3. Shop Oval Engagement Rings　`26`
4. Lab-Grown Oval Diamonds　`23`
5. Free Shipping & Returns　`23`
6. Lifetime Warranty Included　`26`
7. Honest Pricing, No Gimmicks　`27`
8. Ready-to-Ship Oval Rings　`24`
9. Design Your Oval Ring　`21`
10. Certificate With Every Stone　`28`
11. Gold & Platinum Settings　`24`
12. Oval Lab-Grown Engagement　`25`
13. 0% APR Financing Available　`26`
14. Compare Certified Stones　`24`
15. Find Your Perfect Oval　`22`

**descriptions**（上限 90 字符）

1. Oval lab-grown diamond engagement rings with IGI certificates. Shop ready-to-ship.　`82`
2. One honest price, no fake markdowns. Free shipping, free returns, lifetime warranty.　`84`
3. Choose your oval lab-grown diamond and setting, or design a custom ring with us.　`80`
4. Every lab-grown diamond comes with an IGI report. Check it online before you buy.　`81`

**display_path**（上限 15 字符）

1. engagement　`10`
2. oval　`4`

**callouts**（上限 25 字符）

1. IGI Certified　`13`
2. Free Shipping　`13`
3. Free 30-Day Returns　`19`
4. Lifetime Warranty　`17`
5. Ready to Ship　`13`
6. Custom Designs　`14`

**sitelinks**

| 文字 | 描述 1 | 描述 2 | URL |
|---|---|---|---|
| Oval Engagement Rings | Certified lab-grown oval stones | Solitaire, halo and hidden halo | /engagement-rings/oval |
| Ready to Ship | Lab-grown rings ready to go | Ships fast with tracking | /engagement-rings/ready-to-ship |
| Design Your Own Ring | Pick a lab-grown stone | Then choose your setting | /custom |
| Lab-Grown Diamond Guide | How lab-grown is made | How to read an IGI report | /education/lab-grown-diamonds |

落地页：/engagement-rings/oval

**文案依据**：E5

**需商家确认的条款**：0% APR financing；Free 30-day returns；Free shipping；Lifetime warranty

备注：教育页可对比仿品，但广告文案不出现仿品名。“Honest Pricing” 需要长期价格一致，不做虚高划线价（FTC 16 CFR Part 233）。

#### 广告组 G1-2：LGD Engagement Rings Generic

- 为什么：lab grown diamond engagement ring 热门指数 52、+170% [E4]，lab grown diamond ring 指数 100 [E4]；承接不限定形状的订婚戒需求

| 关键词 | 匹配 | 依据 |
|---|---|---|
| [lab grown diamond engagement ring] | exact | 热门 52、+170% [E4] |
| "lab grown diamond engagement rings" | phrase | 热门 52 [E4] |
| "lab grown engagement ring" | phrase | 核心词（brief）[推断] |
| "lab created diamond engagement ring" | phrase | 核心词 lab created diamond [推断] |
| "lab diamond engagement ring" | phrase | lab diamond rings 指数 21 [E4] |
| "lab grown diamond ring" | phrase | 热门 100、+60% [E4] |
| "buy lab grown diamond engagement ring" | phrase | 购买意图修饰词 [推断] |
| "1 carat lab grown diamond engagement ring" | phrase | 1 carat lab grown diamond +60% [E4] |
| "2 carat lab grown diamond ring" | phrase | lab grown 2 carat diamond 指数 15 [E4] |
| "igi certified lab grown diamond ring" | phrase | IGI +2,100% [E5] |
| "lab grown diamond solitaire ring" | phrase | 订婚戒常见款式 [推断] |
| "marquise lab grown diamond ring" | phrase | marquise +120% [E4] |

否定关键词：`oval`, `earrings`, `studs`, `necklace`, `bracelet`, `loose`, `men's`

##### 广告 G1-2-A：RSA_Engagement_Certified（rsa）

**headlines**（上限 30 字符）

1. Lab-Grown Engagement Rings　`26`
2. IGI Certified Lab-Grown　`23`
3. Lab-Grown Diamond Rings　`23`
4. Free Shipping & Returns　`23`
5. Lifetime Warranty Included　`26`
6. One Honest Price　`16`
7. Shop by Shape & Setting　`23`
8. Ready-to-Ship Rings　`19`
9. Design Your Dream Ring　`22`
10. Certificate With Every Stone　`28`
11. Lab-Grown, Graded by IGI　`24`
12. 0% APR Financing Available　`26`
13. Solitaire, Halo & More　`22`
14. Gold & Platinum Settings　`24`

**descriptions**（上限 90 字符）

1. Lab-grown diamond engagement rings, each with an IGI certificate. Shop by shape.　`80`
2. No fake markdowns. One honest price with free shipping, returns and lifetime warranty.　`86`
3. Round, oval, marquise and more. Pick a lab-grown diamond, then choose your setting.　`83`
4. Check every lab-grown diamond report online. Ready-to-ship and custom rings available.　`86`

**display_path**（上限 15 字符）

1. engagement　`10`
2. lab-grown　`9`

**callouts**（上限 25 字符）

1. IGI Certified　`13`
2. Free Shipping　`13`
3. Free 30-Day Returns　`19`
4. Lifetime Warranty　`17`
5. 0% APR Financing　`16`

**sitelinks**

| 文字 | 描述 1 | 描述 2 | URL |
|---|---|---|---|
| Shop by Shape | Oval, round, marquise and more | All stones lab-grown, certified | /engagement-rings |
| Ready to Ship | Lab-grown rings ready to go | Ships fast with tracking | /engagement-rings/ready-to-ship |
| Design Your Own Ring | Pick a lab-grown stone | Then choose your setting | /custom |
| Wedding Bands | Match your lab-grown ring | Gold and platinum bands | /wedding-bands |

落地页：/engagement-rings

**文案依据**：E5

**需商家确认的条款**：0% APR financing；Free 30-day returns；Free shipping；Lifetime warranty

#### 广告组 G1-3：LGD Stud Earrings

- 为什么：LGD stud earrings +190% [E4]，话题 Lab Grown Diamond Earrings Breakout [E5]；入门/礼品款，购物结果耳钉中位 $297.5 [E136]；客单低，CPA 需单独看

| 关键词 | 匹配 | 依据 |
|---|---|---|
| [lab grown diamond stud earrings] | exact | +190% [E4] |
| "lab grown diamond stud earrings" | phrase | +190% [E4] |
| "lab grown diamond earrings" | phrase | 热门 27 [E4] |
| "lab diamond earrings" | phrase | 热门 27 [E4] |
| "lab grown diamond studs" | phrase | +190% 的变体 [E4] |
| "lab created diamond earrings" | phrase | 核心词变体 [推断] |
| "1 carat lab grown diamond earrings" | phrase | 1 carat +60% [E4] |
| "lab grown diamond earrings gift" | phrase | 礼品场景（母亲节、圣诞）[推断] |
| "14k lab grown diamond studs" | phrase | 话题 14k Breakout [E5] |

否定关键词：`engagement`, `ring`, `necklace`, `bracelet`, `men's`, `hoop`

##### 广告 G1-3-A：RSA_Studs_Gift（rsa）

**headlines**（上限 30 字符）

1. Lab-Grown Diamond Studs　`23`
2. Lab-Grown Stud Earrings　`23`
3. IGI Certified Lab-Grown　`23`
4. A Gift She'll Wear Daily　`24`
5. Free Shipping & Returns　`23`
6. Lifetime Warranty Included　`26`
7. 14K Gold Settings　`17`
8. Gift-Ready Packaging　`20`
9. Shop Lab-Grown Earrings　`23`
10. Classic Four-Prong Studs　`24`
11. One Honest Price　`16`

**descriptions**（上限 90 字符）

1. Classic lab-grown diamond stud earrings in 14K gold. Gift-ready with free shipping.　`83`
2. Every pair of lab-grown diamond studs comes with a lifetime warranty and free returns.　`86`
3. Choose carat weight and metal. Lab-grown, certified and priced honestly.　`72`
4. Holiday gift idea: lab-grown diamond studs, shipped fast in a gift box.　`71`

**display_path**（上限 15 字符）

1. earrings　`8`
2. studs　`5`

**callouts**（上限 25 字符）

1. Free Shipping　`13`
2. Free 30-Day Returns　`19`
3. Lifetime Warranty　`17`
4. Gift Box Included　`17`

**sitelinks**

| 文字 | 描述 1 | 描述 2 | URL |
|---|---|---|---|
| Stud Earrings | Lab-grown studs in 14K gold | Choose your carat weight | /earrings/studs |
| Gifts for Her | Lab-grown earrings and pendants | Gift-ready packaging | /gifts |
| Pendants & Necklaces | Lab-grown diamond pendants | Gold and platinum chains | /necklaces |
| Tennis Bracelets | Lab-grown tennis bracelets | Classic and stackable styles | /bracelets/tennis |

落地页：/earrings/studs

**需商家确认的条款**：14K gold settings；Free 30-day returns；Free shipping；Lifetime warranty；Gift box included

### 广告系列 G2：US_Shopping_Standard_LGD

- 类型：Shopping　目标：Sales
- 预算：$700/月（$23.03/天） [计算: CG4]
- 出价：先用 Manual CPC（可开启 eCPC 观察），起始 CPC $1.00–1.50 [建议]（Shopping 基准 CPC $0.69 为 2018–19 年旧数据 [E37]，需上调后按实际调整）；每月累计约 15 个购买 [建议] 后再考虑 Maximize Conversions
- 为什么：购物卡片里卖家以 Brilliant Earth、Kay、Macy's 等为主 [E134]，图片 + 价格直接比价；预算小，用可控的标准购物广告代替 PMax（PMax 预算低时学习慢、流量不可控）。

| 项 | 设置 |
|---|---|
| 地区 | 美国全国 |
| 商品范围 | 订婚戒 + 耳钉（custom_label_0 = 主推） |
| 网络 | 仅 Google 搜索（关闭搜索合作伙伴） |
| 优先级 | 中 |

系列级否定关键词：`moissanite`, `cubic zirconia`, `cz`, `fake`, `simulated`, `cheap`, `wholesale`, `used`, `mined`, `natural diamond`

#### 广告组 G2-1：Feed_Engagement_and_Studs

- 为什么：按 product_type 分组：订婚戒（购物结果中位 $2,349.5 [E134]）出价高一档，耳钉（中位 $297.5 [E136]）出价低一档 [建议]

##### 广告 G2-1-A：Shopping_FeedTitles（shopping）

**descriptions**

1. Oval Lab-Grown Diamond Engagement Ring, IGI Certified, 14K Yellow Gold　`70`
2. Round Lab-Grown Diamond Solitaire Engagement Ring, IGI Certified, Platinum　`74`
3. Lab-Grown Diamond Stud Earrings, Four-Prong, 14K White Gold　`59`

落地页：/engagement-rings

**素材说明**：商品主图白底、戒指斜侧角度，第二张为上手图；标题以 Lab-Grown Diamond 开头，写清形状、证书、金属；价格与落地页一致，不用虚高原价。

**需商家确认的条款**：14K gold settings

备注：descriptions 这里填的是 Merchant Center 商品标题示例，不是广告文案。

### 广告系列 G3：US_Search_NonBrand_ColoredLGD

- 类型：Search　目标：Sales
- 预算：从 G1 调拨 $300/月左右 [建议]；开启条件：G1 连续 4 周 CPA ≤ $494 [计算: CG10]，且已上架黄钻/粉钻商品
- 出价：Maximize Clicks，CPC 上限 $5 [建议]，依据 [E36]
- 为什么：黄钻 +400%、粉钻 +250% [E4]，Meta 竞品样本里几乎没人主推彩钻 [E45]，是差异化机会；但缺同品类价格数据，先等主线跑通。

| 项 | 设置 |
|---|---|
| 地区 | 美国全国 |
| 语言 | English |
| 网络 | 仅搜索网络 |

系列级否定关键词：`moissanite`, `cubic zirconia`, `sapphire`, `citrine`, `topaz`, `fake`, `natural diamond`

#### 广告组 G3-1：Yellow and Pink LGD

- 为什么：彩钻飙升词 [E4]

| 关键词 | 匹配 | 依据 |
|---|---|---|
| "lab grown yellow diamond" | phrase | +400%，热门 26 [E4] |
| "lab grown yellow diamond ring" | phrase | +400% 变体 [E4] |
| "lab grown pink diamond" | phrase | +250% [E4] |
| "lab grown pink diamond ring" | phrase | +250% 变体 [E4] |
| "fancy color lab grown diamond" | phrase | 彩钻通称 [推断] |

##### 广告 G3-1-A：RSA_ColoredLGD（rsa）

**headlines**（上限 30 字符）

1. Yellow Lab-Grown Diamonds　`25`
2. Pink Lab-Grown Diamonds　`23`
3. Lab-Grown Fancy Color Rings　`27`
4. IGI Certified Lab-Grown　`23`
5. Free Shipping & Returns　`23`
6. Lifetime Warranty Included　`26`
7. Stand Out in Color　`18`

**descriptions**（上限 90 字符）

1. Yellow and pink lab-grown diamond rings, each with an IGI report. Shop the color edit.　`86`
2. Fancy color lab-grown diamonds in gold and platinum. Free shipping and free returns.　`84`

**display_path**（上限 15 字符）

1. lab-grown　`9`
2. colored　`7`

**callouts**（上限 25 字符）

1. IGI Certified　`13`
2. Free Shipping　`13`
3. Lifetime Warranty　`17`

落地页：/colored-diamonds

**需商家确认的条款**：Free shipping；Lifetime warranty

## 4. 测试与优化

**A/B 测试矩阵（每次只测一个变量）**

| 周期 | 变量 | 做法 | 判定 |
|---|---|---|---|
| 第 1–4 周 | RSA 标题主张 | 用固定（pin）标题 1 分别测“IGI Certified”与“One Honest Price” | 点击率和加购率；每个版本至少 1,000 次展示 [建议] |
| 第 3–6 周 | 落地页 | 椭圆分类页 vs 单品详情页 | 加购率、CPA |
| 第 5–8 周 | 价格锚点 | 页面加“起步价”与“赠品机制”对比（参考 MiaDonna 送耳钉 [E144]） | 转化率、客单价 |
| 持续 | 关键词 | 每周看搜索字词报告，加否定词，把高转化长尾词提成 exact | CPA |

**加减预算与关停规则**

- 广告组花费超过 2 倍盈亏平衡 CPA（$988 [计算: CG11]）仍 0 单：暂停该组，预算移到表现最好的组
- G1-3 耳钉组单独看：CPA 高于耳钉客单的一半（约 $149 [计算: CG12]）时降价出价或暂停
- 某组 CPA 连续 2 周 ≤ $494 [计算: CG10] 且预算受限：在总预算内从弱组调拨 20% [建议]
- 智能出价切换后学习期最长 7 天 [E162]，期间不调预算和目标
- 关键词质量分低于 5 [建议]：重写广告或拆分广告组

## 5. 上线排期

| 时间 | 重点 | 对齐主报告日历 |
|---|---|---|
| 第 1–2 周 | 搭账户、追踪、Merchant Center；G1 + G2 上线，Maximize Clicks 积累数据 | 11 月黑五为成交节点（全年预算 9% [计算: CB1]） |
| 第 3–4 周 | 清洗搜索字词、补否定词；标题 A/B；耳钉组发力圣诞礼品 | 12 月圣诞和跨年求婚（12% [计算: CB1]） |
| 第 2 个月 | 累计转化够了切 Maximize Conversions；表现好的组加预算 | 1 月淡季（4% [计算: CB1]）可适当降预算，留到 4 月 |
| 第 3 个月 | 评估是否开启 G3 彩钻；准备 3–4 月求婚季 | 4 月搜索峰值（18% [计算: CB1]）前 4–6 周加码订婚戒 |

*用户预算固定为每月 $2,000 [计算: CG1]；如果后续允许按月浮动，建议参照主报告月度占比，把淡季预算挪到 4–5 月和 11–12 月 [建议]，依据 [E1]。*

## 6. 风险与审核

> ⚠️ FTC 珠宝指南要求在 “diamond” 附近清楚标注非开采 [E114]：每条标题、描述、商品标题都要含 lab-grown。RSA 会随机组合，所以每一条单独都要合规，已在 lint 中逐条检查。

- 商标：不投竞品品牌词，已把 Brilliant Earth、Kay 等加为否定词，避免误触和投诉
- 比价声明：文案里不写“比天然便宜 X%”；如要写，需具体规格对比并留存依据（同规格 $450 vs $2,800–3,200 [E126]）
- Merchant Center：运费、退货、价格必须与落地页一致，否则商品会被拒登；页面写明关税已含（de minimis 已暂停 [E120]）
- 价格下跌：批发价 Q2 同比 -13% [E97]，竞品可能降价，每月复查购物卡片竞价
- 高客单价拒付：开启 3D Secure、签收保价，Google 不承担这部分风险

## 附录 A：计算说明

| 编号 | 说明 | 公式 | 结果 |
|---|---|---|---|
| CB1 | 全年预算的月度分配（按搜索热度加权，节点系数为判断） | 占比_m = max(月均指数_m × 节点系数_m, 15) / Σ × 100，取整后合计 100；节点系数：2 月 ×1.5、5 月 ×1.2、11 月 ×2.2、12 月 ×2.2；指数：1 月 16.8、2 月 23.2、3 月 28.2、4 月 78.8、5 月 58.2、6 月 44.8、7 月 19.2、8 月 18.2、9 月 20、10 月 18、11 月 18.6、12 月 23.2 | 1 月 4%、2 月 8%、3 月 6%、4 月 18%、5 月 16%、6 月 10%、7 月 4%、8 月 4%、9 月 5%、10 月 4%、11 月 9%、12 月 12% |
| CG1 | google 月预算 | 总预算 2000 × 100% | $2,000 |
| CG2 | google 日预算 | 2,000.00 ÷ 30.4 | $65.79 |
| CG3 | 广告系列 G1 预算 | 2,000.00 × 65%，日 = 月 ÷ 30.4 | $1,300/月（$42.76/天） |
| CG4 | 广告系列 G2 预算 | 2,000.00 × 35%，日 = 月 ÷ 30.4 | $700/月（$23.03/天） |
| CG5 | 月点击数（按 CPC） | 2,000.00 ÷ CPC 4.44 | 450 |
| CG6 | 月订单数 | 点击 × CVR 4.50% | 20 |
| CG7 | CPA | 2,000.00 ÷ 订单数 | $98.67 |
| CG8 | 月销售额 | 订单 × 客单价 989 | $20,047 |
| CG9 | ROAS | 销售额 ÷ 月预算 | 10.0x |
| CG10 | 盈亏平衡 CPA | 客单价 989 × 毛利率 50%（假设，可替换） | $494 |
| CGC5 | 保守情景 月点击数 | 2,000.00 ÷ CPC 4.44 | 450 |
| CGC6 | 保守情景 月订单数 | 点击 × CVR 2.78% | 13 |
| CGC7 | 保守情景 CPA | 2,000.00 ÷ 订单数 | $160 |
| CGC8 | 保守情景 月销售额 | 订单 × 客单价 989 | $12,385 |
| CGC9 | 保守情景 ROAS | 销售额 ÷ 月预算 | 6.2x |
| CG11 | 关停阈值 | 盈亏平衡 CPA 494 × 2 | $988 |
| CG12 | 耳钉组 CPA 上限（假设毛利 50%） | 耳钉中位价 297.5 × 50% = 148.75，取整 $149 | $149 |

## 附录 B：数据缺失与假设

- 没有 Keyword Planner 的真实搜索量和 CPC，关键词出价和点击预估都来自行业基准（proxy 品类）
- Shopping CPC 基准是 2018–19 年旧数据 [E37]，起始出价为建议值
- 毛利率按 50% 假设，盈亏平衡 CPA 需按真实成本替换
- 品牌名、网站未提供：落地页只写站内路径，未设品牌词系列
- 彩钻同品类价格缺失，G3 放第二阶段
- 文案中的免运费、30 天退货、终身保修、0% APR 分期、14K 金、礼盒都是示例条款，需商家确认能兑现

## 附录 C：引用证据

- **E1** US 'lab grown diamond' 搜索热度（today 12-m，月均指数）：峰值 2026-04 为 78.8，谷值 2026-01 为 16.8，周峰值 Apr 12 – 18, 2026=100，近 3 月均值较最早 3 月 -4.1% — [trends.google.com](https://trends.google.com/trends/explore?q=lab+grown+diamond&geo=US&date=today+12-m) · 2026-11-04T07:42:44Z
- **E4** US 'lab grown diamond' 相关查询（today 12-m）飙升前列：apple iphone 17 pro max Breakout，lab grown yellow diamond +400%，oval lab grown diamond engagement ring +350%，lab grown pink diamond +250%，pink diamond +200%；热门前列：diamond ring 100，lab grown diamond ring 100，engagement ring 52，lab grown diamond engagement ring 52，lab diamond earrings 27 — [trends.google.com](https://trends.google.com/trends/explore?q=lab+grown+diamond&geo=US&date=today+12-m) · 2026-11-04T07:42:44Z
- **E5** US 'lab grown diamond' 相关主题（today 12-m）飙升前列：Lab Grown Diamond Earrings Breakout，14k Breakout，IGI +2,100%；热门前列：Diamond 100，Synthetic diamond 80，Ring 42，Carat 32，Engagement ring 24 — [trends.google.com](https://trends.google.com/trends/explore?q=lab+grown+diamond&geo=US&date=today+12-m) · 2026-11-04T07:42:44Z
- **E36** US google_search CPC 行业基准（apparel_fashion_jewelry(proxy)，proxy，非实测）：$4.44（2025-04~2026-03），来源 WordStream by LocaliQ Google Ads Benchmarks 2026 — [wordstream.com](https://www.wordstream.com/blog/2026-google-ads-benchmarks) · 2026-11-04T07:42:44Z
- **E37** US google_shopping CPC 行业基准（clothing_apparel(proxy)，proxy，非实测，数据较旧）：$0.69（2018-08~2019-02），来源 WordStream Google Shopping Ads Benchmarks — [wordstream.com](https://www.wordstream.com/blog/ws/2019/04/01/shopping-ads-benchmarks) · 2026-11-04T07:42:44Z
- **E40** US google_search CVR 行业基准（apparel_fashion_jewelry(proxy)，proxy，非实测）：4.50%（2025-04~2026-03），来源 WordStream by LocaliQ Google Ads Benchmarks 2026 — [wordstream.com](https://www.wordstream.com/blog/2026-google-ads-benchmarks) · 2026-11-04T07:42:44Z
- **E45** Meta 广告资料库 'lab grown diamond'（US，active，取前 50 条）：样本 50 条广告、26 个广告主，其中 17 个已投放 ≥90 天；形式 VIDEO×23, DPA×17, DCO×8, CAROUSEL×1, IMAGE×1 — [facebook.com](https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=US&q=lab+grown+diamond&search_type=keyword_unordered&media_type=all) · 2026-11-04T07:42:56Z
- **E97** jckonline.com：Lab-Grown Diamond Wholesale Prices Are in Freefall — [jckonline.com](https://www.jckonline.com/editorial-article/lab-grown-wholesale-freefall) · 2026-11-04T07:43:28Z
- **E114** ftc.gov：The many facets of advertising diamonds with clarity | Federal Trade Commission — [ftc.gov](https://www.ftc.gov/business-guidance/blog/2019/05/many-facets-advertising-diamonds-clarity) · 2026-11-04T07:43:37Z
- **E120** carraglobe.com：US De Minimis Exemption Suspended 2026: What Every Importer and E-Commerce Seller Must Do Now - Carra Globe — [carraglobe.com](https://carraglobe.com/us-de-minimis-exemption-suspended-2026) · 2026-11-04T07:44:01Z
- **E126** cnbc.com：What's behind the fall of diamond prices to record lows — [cnbc.com](https://www.cnbc.com/2026/09/26/whats-behind-the-fall-of-diamond-prices-to-record-lows.html) · 2026-11-04T07:44:36Z
- **E134** Google(us) 'lab grown diamond engagement ring'：自然结果 8 条、广告 0 条、购物 30 条；购物结果价格 30 个，P25 $1120 / 中位数 $2349.5 / P75 $3489（最低 $297.5） — [google.com](https://www.google.com/search?q=lab+grown+diamond+engagement+ring&gl=us&hl=en) · 2026-11-04T07:44:50Z
- **E136** Google(us) 'lab grown diamond stud earrings'：自然结果 7 条、广告 2 条、购物 60 条；购物结果价格 60 个，P25 $191.25 / 中位数 $297.5 / P75 $577.5（最低 $49.99） — [google.com](https://www.google.com/search?q=lab+grown+diamond+stud+earrings&gl=us&hl=en) · 2026-11-04T07:44:50Z
- **E143** renaissancejewel.com（Shopify，USD）公开商品 1000+ 个，价格 P25 $989 / 中位数 $1209 / P75 $1249（最低 $89，最高 $2929）；商品多为近期同步的库存（如裸钻），上新数不反映新品节奏；成品首饰 596 个，P25 $989 / 中位数 $1089 / P75 $1249（最低 $89）；品类：戒指 591 个中位 $989，戒托（不含主石） 404 个中位 $1209，耳饰 5 个中位 $1189 — [renaissancejewel.com](https://www.renaissancejewel.com/products.json) · 2026-11-04T07:45:07Z
- **E144** miadonna.com 首页：Shop Lab Grown Diamond Engagement Rings, Wedding Bands & Fine Jewelry — [miadonna.com](https://www.miadonna.com/) · 2026-11-04T07:45:21Z
- **E162** google 官方规格：智能出价“学习中”状态最长持续天数 = 7 days（"Learning status never lasts more than 7 days"；预算/目标/素材修改不会触发学习状态） — [support.google.com](https://support.google.com/google-ads/answer/13020501?hl=en) · 2026-11-04T08:06:20Z
