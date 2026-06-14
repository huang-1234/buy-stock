# 半导体 optional 标的对比分析

> 基于贝叶斯内在增长估值框架，数据截至 **2026 年 6 月中旬**。范围：**纯半导体**（逻辑/算力、定制硅、WFE 设备、互联、Foundry、IP），**不含存储**（memory/HDD 见 [optional-semiconductor-storage](../optional-semiconductor-storage/readme.md)）。供研究参考，**非投资建议**。

## 标的概览

| Ticker | 公司 | 细分定位 | 详细分析 |
| --- | --- | --- | --- |
| NVDA | NVIDIA | AI GPU + DC 网络（InfiniBand/Spectrum-X） | [NVDA/ana.md](./NVDA/ana.md) |
| AVGO | Broadcom | 定制 ASIC + AI 网络（Tomahawk/Jericho） | [AVGO/ana.md](./AVGO/ana.md) |
| AMD | Advanced Micro Devices | EPYC CPU + Instinct GPU | [AMD/ana.md](./AMD/ana.md) |
| AMAT | Applied Materials | WFE 设备 + advanced packaging | [AMAT/ana.md](./AMAT/ana.md) |
| LRCX | Lam Research | Etch/Deposition WFE（DRAM/logic 受益） | [LRCX/ana.md](./LRCX/ana.md) |
| MRVL | Marvell | DC 交换/光互联/定制 XPU | [MRVL/ana.md](./MRVL/ana.md) |
| INTC | Intel | IDM 2.0 + Foundry 转型 | [INTC/ana.md](./INTC/ana.md) |
| ARM | Arm Holdings | 芯片 IP 授权（CPU/AI 生态） | [ARM/ana.md](./ARM/ana.md) |

---

## 一、核心指标对比

| 维度 | NVDA | AVGO | AMD | AMAT | LRCX | MRVL | INTC | ARM |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 股价（约） | ~$215 | ~$372 | ~$437 | ~$427 | ~$370 | ~$245 | ~$118 | ~$130 |
| 市值 | ~$5.2T | ~$1.75T | ~$687B | ~$340B | ~$459B | ~$216B | ~$568B | ~$337B |
| TTM / 前瞻收入 | FY27 ~$360B | FY26 ~$110B | FY26 ~$45B | FY26 ~$32B | FY26 ~$24B | FY27 ~$11.5B | FY26 ~$56B | FY26 ~$4.5B |
| 前瞻 P/E | ~25–30x | ~35–40x | ~32–35x | ~30–41x | ~55–70x | ~40–63x | ~25–30x | ~80–100x |
| 加权内在 3–5Y CAGR | ~38% | ~35% | ~28% | **~22%** | ~24% | ~30% | ~12% | ~20% |
| 市场隐含 CAGR | ~42% | ~38% | ~32% | ~18% | ~28% | ~35% | ~8% | ~25% |
| 内在 − 隐含（gap） | **−4pp** | **−3pp** | **−4pp** | **+4pp** | **−4pp** | **−5pp** | **+4pp** | **−5pp** |
| 12M 股价回报 | +39% | +48% | +38% | **−2%** | +80% | +245% | +7% | +15% |
| 距 52W 高 | **−9%–26%** | **−25%** | −10% | −15% | 近高 | −7% | −20% | −15% |
| 6 月回调 | **−7%–9%** | **−13%–22%** | −5% | 持平 | 随板块 | −5% | 持平 | 小幅 |
| 股价-基本面背离 | 轻度（回调后） | 轻度（回调后） | 匹配 | **落后** | 中度 | 中度 | **落后** | 匹配 |
| 估值状态 | 合理偏高 | 合理（回调后） | 合理偏高 | **合理** | 高估可交易 | 高估可交易 | **低估** | 高估可交易 |
| 盈利质量 | 极强（GM 75%） | 极强（OM 67%） | 改善中 | 稳定 | 强（margin 扩张） | 改善中 | 弱/转型 | 强（royalty） |
| AI 暴露度 | **最高** | **最高** | 高 | 中（间接） | 中（间接） | 高 | 低–中 | 中（生态） |

**解读：** 6 月中旬 AI semi 板块经历 **「record 财报 → 指引 delta 失望 → 板块回调」**（AVGO 触发链式反应）。回调后 NVDA/AVGO gap 收窄，**AMAT 仍为唯一「股价落后 + gap 为正」的核心标的**；INTC 为转型期权。

---

## 二、AI 半导体栈结构

```text
IP 层             ARM（CPU/AI 指令集授权）
       ↓
算力层            NVDA GPU  ·  AMD MI/EPYC  ·  AVGO 定制 ASIC
       ↓
互联层            NVDA InfiniBand/Spectrum-X  ·  AVGO Tomahawk/Jericho  ·  MRVL 交换/光模块
       ↓
制造层            TSMC/Intel Foundry/Samsung（INTC 为 US option）
       ↓
设备层            AMAT · LRCX · KLAC（本表 AMAT/LRCX）
```

**2026 年 6 月行业快照：**
- Hyperscale 2026 capex 预计 **$600B+**（+36% YoY），AI infra 为主
- NVDA Q2 FY27 指引 **$91B**；AVGO Q3 FY26 **$29.4B**（AI semi $16B）
- SEMI：2026 全球 300mm fab equipment **+18% 至 $133B**
- 6 月板块回调主因：**估值对 guidance delta 极度敏感**，非 demand 断崖

---

## 三、12–18 个月回报情景矩阵

假设 hyperscale capex 不断崖、Blackwell/Rubin + 定制 ASIC ramp 按计划：

| 情景 | NVDA | AVGO | AMD | AMAT | LRCX | MRVL | INTC | ARM |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| **Bull** | +40%–60% | +45%–65% | +35%–50% | +35%–50% | +30%–45% | +40%–55% | +50%–80% | +30%–45% |
| **Base** | +15%–25% | +20%–35% | +15%–25% | **+20%–30%** | +10%–20% | +10%–25% | +10%–20% | +10%–20% |
| **Bear** | −20%–30% | −20%–30% | −20%–30% | −15%–20% | −20%–30% | −25%–35% | −20%–30% | −25%–35% |
| **期望回报（加权）\*** | +18%–25% | +20%–30% | +15%–22% | **+18%–25%** | +12%–18% | +12%–18% | +15%–25% | +10%–18% |

\* 期望回报 = 0.25×Bull + 0.50×Base + 0.25×Bear 的粗略区间。

---

## 四、风险调整后回报排名

| 排名 | Ticker | 逻辑 |
| ---: | --- | --- |
| **1** | **AMAT** | gap **+4pp**；12M **−2%** 未 FOMO；WFE 超级周期；Morningstar 称 AMAT 为 equipment 组「最佳 disconnect」 |
| **2** | **AVGO** | 6 月 **−22% 回调** 后 gap 收窄；FY27 AI semi **>$100B** 路径；FCF $10B/qtr；定制 ASIC 70% 份额 |
| **3** | **NVDA** | 距 52W 高 **−26%**；Q2 $91B 指引；Blackwell ramp；回调后 risk/reward 改善 |
| **4** | **AMD** | Meta **6GW** MI450 绑定；内在 ≈ 隐含；MI450 H2 ramp 为 catalyst |
| **5** | **INTC** | gap **+4pp**；foundry 期权；**12M +7%** 落后；小比例配置 |
| **6** | **LRCX** | MS Overweight；DRAM/NAND WFE 强；但 P/E ~69x、China 风险 |
| **7** | **MRVL** | FY28 $16.5B 路径；P/S ~19x 已 price-in |
| **8** | **ARM** | Royalty 质量高；P/E ~80–100x 限制 upside |

### 分场景首选

| 投资目标 | 首选 | 理由 |
| --- | --- | --- |
| **风险调整后期望回报最高** | **AMAT** | 卖铲人 + 未 re-rate + gap 为正 |
| **AI 算力回调后买入** | **NVDA / AVGO** | 6 月 pullback 改善 entry；AVGO 定制 ASIC 分散 GPU 风险 |
| **二号位算力 + 性价比** | **AMD** | MI450/Meta 6GW；P/E ~35x vs NVDA 质量折扣 |
| ** asymmetric 转型** | **INTC** | Foundry 2027 H2 catalyst；与 AI 龙头低相关 |
| **设备周期弹性** | **LRCX** | DRAM etch/deposition 受益；次于 AMAT 因估值更高 |
| **当前不建议追高** | **ARM** | P/E ~80–100x；royalty 慢变量 vs 股价快变量 |

### 综合判断

> **若以「从现在买入到 2027 年中」的期望投资回报率排序：**
>
> **AMAT > AVGO（回调后）≈ NVDA（回调后）> AMD > INTC > LRCX > MRVL > ARM**

- **6 月回调改变了算力层 entry**：NVDA/AVGO 从「轻度 FOMO」变为「合理偏高估」，与 5 月「record 财报即新高」不同。
- **AMAT 仍是板块锚定**：不受 guidance delta 游戏影响，直接受益于 $133B WFE 支出。
- **INTC 适合 10%–15% 期权式** 配置，与 AMAT/NVDA 形成 US semi 全栈。

---

## 五、组合配置建议（条件化）

| 风险偏好 | 建议配置 | 核心逻辑 |
| --- | --- | --- |
| **均衡（推荐）** | **AMAT 35% + NVDA 25% + AVGO 20% + AMD 20%** | 卖铲人 + 算力双雄 + 定制 ASIC + 二号位 |
| **进攻** | **NVDA 30% + AVGO 30% + AMD 25% + AMAT 15%** | AI capex 直接 exposure；接受 −25% 回撤 |
| **防守** | **AMAT 50% + INTC 25% + AMD 25%** | 低 FOMO + 转型期权 + 适度 AI |
| **纯算力** | **NVDA 45% + AVGO 35% + AMD 20%** | 不含设备；高 beta |
| **当前不建议** | **ARM 重仓 / MRVL 追高** | 估值已充分 |

---

## 六、统一验证窗口（2026 H2）

| Ticker | 下一季 | 预计日期 | 关键验证 |
| --- | --- | --- | --- |
| **NVDA** | FY27 Q2 | **~8 月 27 日** | Rev ~$91B；Blackwell/Rubin；GM ~75% |
| **AVGO** | FY26 Q3 | **~9 月 3 日** | Rev ~$29.4B；AI semi $16B；VMware |
| **AMD** | CY Q2 | **~8 月 5 日** | Rev ~$11.2B；MI450 进展 |
| **AMAT** | FY26 Q3 | **~8 月 14 日** | WFE 订单；DRAM mix |
| **LRCX** | FY26 Q4 | **~8 月 20 日** | Rev $6.2–7B guide 兑现 |
| **MRVL** | FY27 Q2 | **~8 月底** | Rev $2.7B；FY27 $11.5B |
| **INTC** | CY Q2 | **~7 月 23 日** | Foundry；18A |
| **ARM** | FY26 Q1 | **~8 月 6 日** | Royalty；AI PC/DC IP |

**组合级证伪：**
- NVDA + AVGO 同时下调下季指引
- Hyperscale 削减 2027 AI capex（MSFT/AMZN/GOOG/META 集体）
- WFE 订单连续两季 YoY 负增长
- 美中 export control 显著扩大至 AI 网络/设备

---

## 七、与存储板块交叉引用

| 主题 | 半导体（本目录） | 存储（[semi-storage](../optional-semiconductor-storage/readme.md)） |
| --- | --- | --- |
| AI bottleneck | GPU/ASIC 算力 | HBM/DRAM/NAND |
| 卖铲人 | AMAT、LRCX | 同左 + memory capex 更猛 |
| 当前最佳 entry | AMAT、回调后 NVDA/AVGO | AMAT、SNDK（周期） |
| 不宜追高 | ARM、MRVL | WDC（+900%） |

---

## 八、一句话总结

**2026 年 6 月 AI semi 板块因 AVGO guidance delta 集体回调，NVDA/AVGO 从 FOMO 边缘回到「合理偏高估」，risk/reward 改善；AMAT 仍是唯一股价落后基本面、gap 为正的 WFE 锚定；AMD 为二号位算力；INTC 为 US foundry 期权——当前价位优先 AMAT + 回调后的 NVDA/AVGO 组合，而非 ARM/MRVL 追高。**

---

*各标的完整 13 节分析见子目录 `ana.md`。框架：`.cursor/skills/bayesian-intrinsic-growth-valuation/`。*
