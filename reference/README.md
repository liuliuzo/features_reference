# Reference 综合参考库

本仓库是博瑞康与 BGSSAI 业务系统的核心参考资料枢纽，对齐本地三大参考体系。

---

## 本地参考目录架构

| 序号 | 规范目录 | 目录定位 | 对应本地物理路径 |
| :---: | :--- | :--- | :--- |
| **01** | `reference-github` | **参考代码库** | `/home/github/reference-github` (`C:\Users\lzhao3730\Desktop\github\reference-github`) |
| **02** | `reference-prototypes` | **参考原型设计** | `/home/github/reference-prototypes` (`C:\Users\lzhao3730\Desktop\github\reference-prototypes`) |
| **03** | `reference` | **其它参考资料** | `/home/github/reference` (`C:\Users\lzhao3730\Desktop\github\reference`) |

---

## 目录详述与指引

### 目录 01：参考代码库 (`reference-github`)
归档与业务系统相关的开源技术实现、核心中间件架构与算法原型：
- **AECG / 动态心电分析**：12导联静息与长程动态心电事件分级、数据传输协议与波形渲染；
- **通讯网关与渠道交互**：企业微信 / 微信公众号集成、回调签名校验、会话管理、模板消息下发与幂等处理；
- **任务调度与状态机**：随访计划多节点流转、状态版本乐观锁（`version` 条件更新）、SLA 履约监控；
- **数据管道与批处理**：患者与体检数据 Excel / CSV 批量导入、整批校验防污染、脱敏与历史数据对齐。

### 目录 02：参考原型设计 (`reference-prototypes`)
归档所有系统交互原型、UI 高清设计图与静态演练页面：
- **AECG 医生工作站原型**：52 个完整交互界面，覆盖筛查干预、随访管理、精细化管理与系统功能；
- **多端与平台原型**：微信端互动、医生端工作台、管理端运营总览及客服工单原型；
- **交互索引**：支持双栏对照、模块检索与离线独立运行。

### 目录 03：其它参考资料 (`reference`)
归档临床医学指南、行业专家共识、运营标准及产品需求输入依据：
- **`clinical/` 临床专家共识与指南**：
  - `ecg-risk-stratification-consensus.md`：《远程心电图危险分级诊断中国专家共识》（CRITICAL / WARNING / NORMAL 三级标准）；
  - `cardiovascular-chronic-care-guidelines.md`：心血管疾病全周期随访与闭环结案规范。
- **`operations/` 运营 SOP 与规约**：
  - `managed-operations-sop.md`：全托管患者运营工作规范（核对身份、人工触达留痕、下次计划重试）；
  - `hospital-collaboration-roles.md`：医护责任边界、审核授权与追加审计留痕机制。
- **`specifications/` 规格与协议**：
  - `prd-cardiovascular-full-cycle.md`：全周期平台规格；
  - `data-exchange-specification.md`：医院 HIS/EMR 接口交接字段规约。

---

## 本地浏览导航

在浏览器中打开根目录的 [`index.html`](index.html) 即可查阅参考导航门户。
