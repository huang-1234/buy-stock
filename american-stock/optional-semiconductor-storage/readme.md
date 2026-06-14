# 半导体 & 存储 optional 标的对比分析

> 基于贝叶斯内在增长估值框架，数据截至 **2026 年 6 月中旬**。供研究参考，**非投资建议**。

## 标的概览

| Ticker | 公司 | 细分定位 | 详细分析 |
| --- | --- | --- | --- |
| MU | Micron | DRAM/NAND/HBM 一体化存储 | [MU/ana.md](./MU/ana.md) |
| SNDK | SanDisk | 纯 NAND Flash（WDC 2025 分拆） | [SNDK/ana.md](./SNDK/ana.md) |
| WDC | Western Digital | 纯 HDD 大容量存储 | [WDC/ana.md](./WDC/ana.md) |
| STX | Seagate | HDD 双寡头 + HAMR Mozaic | [STX/ana.md](./STX/ana.md) |
| AMAT | Applied Materials | 半导体/WFE 设备（卖铲人） | [AMAT/ana.md](./AMAT/ana.md) |
| MRVL | Marvell | DC 互联/交换/定制 XPU | [MRVL/ana.md](./MRVL/ana.md) |
| AMD | Advanced Micro Devices | EPYC CPU + Instinct GPU | [AMD/ana.md](./AMD/ana.md) |
| INTC | Intel | IDM 2.0 + Foundry 转型 | [INTC/ana.md](./INTC/ana.md) |

---

## 一、核心指标对比

| 维度 | MU | SNDK | WDC | STX | AMAT | MRVL | AMD | INTC |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 股价（约） | ~$996 | ~$1,833 | ~$594 | ~$801 | ~$427 | ~$245 | ~$437 | ~$118 |
| 市值 | ~$1.11T | ~$273B | ~$164B | ~$176B | ~$340B | ~$216B | ~$687B | ~$568B |
| TTM / 前瞻收入 | FY26 ~$100B+ | FY26 ~$29B | FY26 ~$14B | FY26 ~$13B | FY26 ~$32B | FY27 ~$11.5B | FY26 ~$45B | FY26 ~$56B |
| 前瞻 P/E | ~10–12x | ~5–8x | ~30–35x | ~35–40x | ~30–41x | ~40–63x | ~32–35x | ~25–30x（non-GAAP） |
| 加权内在 3–5Y CAGR | **~35%** | ~28% | ~18% | ~17% | **~22%** | ~30% | ~28% | ~12% |
| 市场隐含 CAGR | ~40% | ~15%* | ~25% | ~22% | ~18% | ~35% | ~32% | ~8% |
| 内在 − 隐含（gap） | **−5pp** | **+13pp*** | **−7pp** | **−5pp** | **+4pp** | **−5pp** | **−4pp** | **+4pp** |
| 12M 股价回报 | +760% | +3,800%† | +900% | +450% | −2% | +245% | +38% | +7% |
| YTD 回报 | +196% | +250% | +45% | +44% | −2% | +22% | +38% | +7% |
| 股价-基本面背离 | 严重 | 中度‡ | 严重 | 中度 | **匹配** | 中度 | 轻度 | **落后** |
| 估值状态 | 高估可交易 | 合理/低估周期 | 泡沫边缘 | 高估可交易 | **合理** | 高估可交易 | 合理偏高 | **低估** |
| 盈利质量 | 极强（GM 81%） | 极强但纯周期 | 强（GM 51%） | 强（GM 47%） | 稳定（GM 50%） | 改善中 | 改善中 | 弱/转型 |
| 周期属性 | 高（memory） | **最高**（NAND） | 中（结构需求） | 中 | **低**（WFE） | 低 | 低 | 中 |
| Beta / 弹性 | 高 | **最高** | 高 | 高 | 中 | 高 | 高 | 中 |

\* SNDK 市场隐含 CAGR 基于「周期峰值 earnings 不可持续」的折价定价；若 AI NAND  tight supply 延续 2–3 年，隐含增速被系统性低估。  
† 自 2025/2 分拆上市约 $38 起算。  
‡ 股价暴涨但 forward P/E 仅 ~6x，反映市场对周期可持续性的怀疑，而非 FOMO 泡沫。

**解读：** gap = 内在 CAGR − 市场隐含 CAGR。存储/memory 标的普遍 12M 暴涨，多数 gap 为负（市场更乐观）。**AMAT、INTC、SNDK（周期视角）** 为少数 gap ≥ 0 或接近 0 的标的。

---

## 二、行业结构图（AI 存储栈）

```text
AI 算力层          NVDA GPU / AMD MI / 定制 ASIC
       ↓
HBM/DRAM 层        MU · SK Hynix · Samsung        ← 最紧 bottleneck
       ↓
NAND/SSD 层        SNDK · MU · Samsung            ← 热/温数据
       ↓
Enterprise Flash   PSTG(Everpure) · 阵列 OEM      ← 企业热存储（未纳入本表）
       ↓
HDD 冷/归档层      WDC · STX                      ← 80% hyperscale 存量数据
       ↓
WFE 设备层         AMAT · LRCX · KLAC             ← capex 卖铲人
       ↓
DC 互联/定制硅     MRVL · AVGO                    ← 交换/NVLink/CPO/XPU
```

**关键观察（2026 年 6 月）：**
- HBM 三巨头 2026 产能售罄，Micron 仅满足客户 50–65% 需求（CEO 口径）
- DRAM/NAND 因 cleanroom 向 HBM 倾斜而供给收紧， Goldman 称「史上最深 memory 短缺」或延续至 2028
- HDD nearline 产能 2026–2027 基本 commit（WDC/STX 管理层口径）
- WFE 2026 全球支出向 $115–126B optimistic scenario 上行（Citi）

---

## 三、12–18 个月回报情景矩阵

假设 AI capex 不断崖、memory/HDD tight supply 延续至 2027 H1：

| 情景 | MU | SNDK | WDC | STX | AMAT | MRVL | AMD | INTC |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| **Bull** | +30%–50% | +50%–80% | +25%–40% | +20%–35% | +35%–50% | +40%–60% | +35%–50% | +50%–80% |
| **Base** | +5%–15% | +15%–30% | +5%–15% | +5%–15% | **+20%–30%** | +10%–25% | +15%–25% | +10%–20% |
| **Bear** | −25%–35% | **−40%–55%** | −25%–35% | −20%–30% | −15%–20% | −25%–35% | −20%–30% | −20%–30% |
| **期望回报（加权）\*** | +8%–12% | +12%–22% | +5%–10% | +5%–10% | **+18%–25%** | +12%–18% | +15%–22% | +15%–25% |

\* 期望回报 = 0.25×Bull + 0.50×Base + 0.25×Bear 的粗略区间，非精确模型。

---

## 四、风险调整后回报排名

| 排名 | Ticker | 逻辑 |
| ---: | --- | --- |
| **1** | **AMAT** | 内在 ~22% > 隐含 ~18%；WFE 超级周期 + memory/logic/advanced packaging 三线受益；**12M 仅 −2%、未 FOMO**；FY26 equipment +30% 指引；P/S ~11x 低于 memory  peers |
| **2** | **SNDK** | 周期视角 gap **+13pp**（市场按峰值 earnings 折价）；Q4 指引 $8B rev / GM 80% / EPS $30+；NBM 多年合约提供 visibility；**Bear 尾部 −40% 最大**，需严格仓位 |
| **3** | **INTC** | 唯一大型 **gap +4pp + 股价落后基本面**；18A foundry + Q1 beat；P/B ~4.8x vs 同行；foundry 期权未 price-in；执行风险高但 asymmetry 大 |
| **4** | **AMD** | MI450/Meta 6GW 绑定 + DC +57% YoY；内在 ~28% ≈ 隐含 ~32%；P/E ~35x FY26 有 growth premium 但非泡沫 |
| **5** | **MU** | 基本面最强（Q3 $33.5B / GM 81% / HBM 售罄）；但 12M +760%、$1T 市值已 price-in 超级周期；**适合持有而非追高** |
| **6** | **MRVL** | FY27 $11.5B / FY28 $16.5B 指引上修；DC 占 75%；但 P/S ~19x FY27、已 +245% 自低点 |
| **7** | **STX** | HDD 结构需求 + Mozaic HAMR；与 WDC 类似但 12M +450% 略低于 WDC；双寡头定价权 |
| **8** | **WDC** | HDD 逻辑正确但 12M +900%、P/E 畸高（基数效应）；**从当前价位追入容错最低** |

### 分场景首选

| 投资目标 | 首选 | 理由 |
| --- | --- | --- |
| **风险调整后期望回报最高** | **AMAT** | 卖铲人逻辑、未 FOMO、gap 为正、WFE 周期第二段上行 |
| **周期弹性 + 潜在 re-rating** | **SNDK** | forward P/E ~6x 隐含极度悲观；若 tight supply 延续 2–3Y 则有大幅重估空间 |
| ** asymmetric 转型期权** | **INTC** | 股价落后、foundry 2027 H2 catalyst；适合小比例期权式配置 |
| **AI 算力直接 exposure** | **AMD** | MI450 H2 2026 ramp + EPYC 份额；比 NVDA 便宜但 execution 风险更高 |
| **质量优先、可接受估值** | **MU** | HBM/DRAM 龙头；回调后（距 52W 高 −18%）优于追 WDC/SNDK 高点 |
| **当前不建议新开仓追高** | **WDC** | +900% 已透支 HDD 结构故事；miss 一次可能 −30% |

### 综合判断

> **若以「从现在买入到 2027 年中」的期望投资回报率排序：**
>
> **AMAT > SNDK（条件满足时）≈ INTC（期权式）> AMD > MU > MRVL > STX > WDC**

- **AMAT 是当前综合回报率最高的选择**：memory 超级周期的上游受益者，自身未参与 memory 股价 FOMO，FY26–27 EPS 增速 30%+ 可见，Base case +20%–30% 概率最高。
- **SNDK 仅在确认 NAND tight supply 延续 + NBM 合约兑现时，才可能超越 AMAT**——在此之前 Bear 尾部 −40%–55% 过大，宜小仓。
- **INTC 适合作为组合中的「转型期权」**，不宜重仓，但 gap 为正且股价 12M 仅 +7%，与 memory FOMO 形成对冲。
- **MU 基本面最佳**，但从 $1T 市值算继续大涨需 HBM4 全面 ramp + GM 维持 80%+，更适合回调分批。
- **WDC/STX HDD 故事正确**，但 12M +450%–900% 已将 2027 年 earnings 大幅 forward price。

---

## 五、组合配置建议（条件化）

| 风险偏好 | 建议配置 | 核心逻辑 |
| --- | --- | --- |
| **均衡（推荐）** | **AMAT 40% + MU 25% + AMD 20% + INTC 15%** | 卖铲人锚定 + memory 质量 + 算力 + 转型期权 |
| **进攻** | **AMAT 30% + SNDK 25% + MU 25% + AMD 20%** | 周期弹性；SNDK 小比例博 re-rating |
| **防守** | **AMAT 50% + INTC 30% + MU 20%** | 低 FOMO + 转型 asymmetry + memory 龙头 |
| **纯存储** | **MU 40% + SNDK 20% + STX 20% + WDC 20%** | 全栈 storage；**仅适合已理解周期风险者** |
| **当前不建议** | **单押 WDC/STX/SNDK 追高** | 12M 涨幅已透支 1–2 年 earnings |

---

## 六、统一验证窗口（2026 H2）

### 下一季财报时间表（2026 年 6 月中旬视角）

| Ticker | 报告季度 | 覆盖期间 | 预计日期 | 时段 | 关键验证 |
| --- | --- | --- | --- | --- | --- |
| **MU** | FY2026 Q3 | ~3–5 月 | **6 月 24 日（周三）** | 盘后 AMC | GM ≥81%、HBM 指引、CapEx >$25B |
| **SNDK** | FY2026 Q4 | ~4–6 月 | **7 月底–8 月初** | 盘后 | Rev $7.75–8.25B、NBM 进展、DC mix |
| **STX** | FY2026 Q4 | ~4–6 月 | **8 月初** | 盘后 | Mozaic 占比、nearline 分配 |
| **WDC** | FY2026 Q4 | ~4–6 月 | **8 月初** | 盘后 | Rev $3.65B、GM 51%+ |
| **AMAT** | FY2026 Q3 | ~5–7 月 | **8 月 14 日前后** | 盘后 | WFE 订单、DRAM 设备 mix |
| **MRVL** | FY2027 Q2 | ~5–7 月 | **8 月底** | 盘后 | Rev $2.7B、FY27 $11.5B 维持 |
| **AMD** | CY2026 Q2 | 4–6 月 | **8 月 5 日前后** | 盘后 | Rev ~$11.2B、MI450 进展 |
| **INTC** | CY2026 Q2 | 4–6 月 | **7 月 23 日前后** | 盘后 | Foundry $5B+、18A 客户 |

**时间线（美东）：**

```text
6/24 (三)  MU    FY26 Q3        盘后  ← 本轮最重要 catalyst（GM 81% 能否维持）
7/23 (四)  INTC  Q2 2026        盘后  ← Foundry 客户/18A
8/初       SNDK  FY26 Q4        盘后  ← NAND 周期验证
8/初       WDC   FY26 Q4        盘后
8/初       STX   FY26 Q4        盘后
8/5  (三)  AMD   Q2 2026        盘后
8/中       AMAT  FY26 Q3        盘后
8/底       MRVL  FY27 Q2        盘后
```

### 组合级证伪（任一触发则下调整体 semi/storage 敞口）

- MU Q3 GM < 78% 或下调 HBM/DRAM 供给展望
- 两家以上 memory/HDD 公司 miss 或下调指引
- Hyperscale（MSFT/AMZN/GOOG/META）集体削减 2027 DC capex
- DRAM/NAND ASP 季度环比下滑 >10%（TrendForce / 公司口径）
- SNDK 毛利率单季下滑 >10ppt（周期拐点信号）

---

## 七、未纳入但值得观察

| Ticker | 定位 | 未纳入原因 |
| --- | --- | --- |
| NVDA | AI GPU 龙头 | 不在「存储/广义 semi 设备」核心；估值已充分讨论 |
| AVGO | Networking + 定制 ASIC | 体量过大、已接近 fair value；MRVL 覆盖类似主题 |
| LRCX/KLAC | WFE 设备 | 与 AMAT 高度相关；AMAT 为代表 |
| PSTG (P) | Enterprise all-flash | FY26 增速 ~15%、偏稳健；HDD/ NAND 弹性更大 |
| TXN/ADI | 模拟芯片 | AI 暴露度低；周期不同步 |

---

## 八、一句话总结

**2026 年 AI memory 超级周期下，MU/SNDK/WDC/STX 基本面均强，但 memory/HDD 标的 12M 涨幅 450%–3,800% 已严重领先 posterior 更新；当前价位风险调整后期望回报最高的是尚未 FOMO 的 WFE 卖铲人 AMAT，其次是市场仍按周期峰值折价、若 tight supply 延续 2–3 年存在 re-rating 空间的 SNDK，以及股价落后、foundry 期权未定价的 INTC；MU 质量最佳宜回调买，WDC 故事正确但已从当前价位透支最多未来。**

---

*各标的完整 13 节分析见子目录 `ana.md`。框架：`.cursor/skills/bayesian-intrinsic-growth-valuation/`。*
