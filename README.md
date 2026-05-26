# 👋 Hi, I'm [Ryan] | 新范式开发者

> **"不写废代码，只做业务终结者。"**
> 
> 懂业务 · 善用 AI 杠杆 · 80小时碎片交付 · 支撑39个项目全面投产

[![ASP.NET Core](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet)]()
[![Vue](https://img.shields.io/badge/Vue-3.x-4FC08D?logo=vuedotjs)]()
[![SQL Server](https://img.shields.io/badge/SQL_Server-Linux-CC2927?logo=microsoftsqlserver)]()
[![AI Powered](https://img.shields.io/badge/AI-Cursor_+_Copilot-FF6B6B?logo=openai)]()

---

## 🚀 核心战绩：QES 物业质量评估系统

从 0 到 1，**20天 × 每天4小时碎片时间**，在出差路上边用边改，交付支撑企业核心运转的数字基座。

| 指标 | 数据 | 业务价值 |
| :--- | :--- | :--- |
| ⏱️ **有效工时** | 80 小时 | 传统团队 2-3 个月工作量 |
| 🏢 **覆盖规模** | 39 个项目 / 3 个区域公司 | 全面投产，非实验室 Demo |
| 📊 **自动化报告** | 156 份项目 + 12 份区域总结 | 单份耗时 3h → 45min，提效 75% |
| 🔌 **系统体量** | 35 Controllers / 150+ APIs / 20+ Tables | 完整闭环：检查→分析→报告→整改 |
| 📱 **使用门槛** | 浏览器即 APP，零安装 | 一线员工主动催更的"香馍馍" |

---

## 🧠 技术亮点：不只是 CRUD

### 1. 柔性三表架构 — 解决"业务规则多变"
抛弃僵化单表，构建 `CheckItemLibrary` → `CheckContentItems` → `ProblemOptions` 三表模型：
- ✅ 支持 **排他组互斥**、一票否决、自定义算分
- ✅ 系统预设与个人创建 **权限隔离** (`CreatedByName` 过滤)
- ✅ 检查项库可独立扩展，不影响历史数据

### 2. 无模板 Word 直出 — 消灭"模板维护噩梦"
踩坑 `SkiaSharp` 命名空间冲突后，采用 `DocX + 原生 OpenXML` 代码直出：
- ✅ 现场图片原生注入与标注，无需第三方渲染
- ✅ 含重点问题矩阵、共性问题表格、AI 整改建议
- ✅ 报告历史全量追溯，支持重下载

### 3. 极简工程化 — "够用就好"的生产级底座
没有 K8s，没有过度设计，用最稳的技术栈做最可靠的事：
- ✅ **双环境隔离**：生产/ 测试 物理分离
- ✅ **安全发布**：`rsync --exclude='appsettings*.json'` 防配置覆盖
- ✅ **验活兜底**：发布后自动 `curl /api/Server/status` 确认健康
- ✅ **浏览器即APP**：Vue3 响应式 + JWT 轻量认证，砍掉 80% 原生开发成本

---

## 🛠️ 技术栈

| 层级 | 技术选型 | 说明 |
| :--- | :--- | :--- |
| **后端** | ASP.NET Core 8.0 + EF Core 8.0 | Web API + Code First 迁移 |
| **前端** | Vue 3 + Element Plus + ECharts | Composition API + 数据可视化 |
| **数据库** | SQL Server (Linux Docker) | 20+ 核心表，软删除，JSON 字段 |
| **报告** | DocX + OpenXML | 无模板代码直出 Word |
| **部署** | Nginx + systemd + rsync | 反向代理 + 进程管理 + 安全同步 |
| **AI** | Cursor + Copilot | 基础代码生成，精力聚焦业务建模 |

---

## 💡 我的方法论 (Playbook)

| # | 原则 | 实践 |
| :--- | :--- | :--- |
| 01 | **业务即需求，用户即测试** | 在现场改代码，5分钟修复，当场全流程验证，继续使用！ |
| 02 | **工具链 > 造轮子** | AI 生成基础代码，精力留给业务建模与边界校验 |
| 03 | **浏览器即 APP** | 响应式 Web + JWT，换取一线"零安装、打开即用" |
| 04 | **先跑通再完美** | 20天交付 MVP，上线后根据真实反馈持续迭代 |

---

## 🔮 演进路线

- [x] **Phase 1**：检查闭环 + Word 直出 + 权限隔离 + 移动端兼容 *(已完成)*
- [ ] **Phase 2**：数据自动备份 + 操作审计 + PDF 导出 + Pinia 状态管理
- [ ] **Phase 3**：设备二维码巡检 + 弱网离线缓存 + AI 趋势预测 + 消息预警

---

## 📫 联系我

如果你需要一个能把模糊业务痛点转化为高可用数字基座的伙伴：

- 📧 Email: [3165184647@qq.com]

---

<div align="center">
  <sub>Built with ❤️ & AI | © 2026 New Paradigm Developer</sub>
</div>
