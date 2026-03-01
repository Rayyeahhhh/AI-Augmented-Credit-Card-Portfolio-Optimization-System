# AI-Augmented-Credit-Card-Portfolio-Optimization-System
A decision-support system that leverages AI agents to transform transaction data into strategic revenue recommendations.


## 專案流程
1. Step 1
  A. Analysis Agent: 作我們在prompt請他做的分析
  B. EDA Insight Agent: 自動讀取結果，初步假設
  C. Hypothesis Validator Agent: 挑戰假說，要求數據支持，讓假說變的更具體，或是擬定分析的下一步。
2. Step 2 — Data Processing Agent
---
unfinsished
---
功能：

Feature engineering（RFM）

Usage trend feature

Spending volatility

Category concentration

這一步不要讓 LLM 寫 code。

你自己寫，LLM 只輔助。

🔹 Step 3 — Modeling Agent

任務：

KMeans segmentation

Usage decline classifier

SHAP explanation

產出不是模型，而是：

Segment profile table

Risk score distribution

🔹 Step 4 — Auto Labeling Agent

這是你加分的地方。

讓 LLM 根據 segment 結果：

自動生成：

“Young occasional spenders”

“High value but declining users”

“Stable heavy users”

這個很顧問。

🔹 Step 5 — Insight & Strategy Agent

輸入：

segment label

risk distribution

key behavioral driver

輸出：

3 actionable strategy

預期 impact mechanism

潛在風險

🔹 Step 6 — Financial Impact Simulation Agent

這裡一定要有公式：

Incremental Revenue =
Affected Customers × Lift × Avg Spend × Margin

讓 LLM 幫你做 scenario analysis。
