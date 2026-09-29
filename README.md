# ⚡ xbeeear · 节奏与时间骨架 (Academic Time-Skeleton & Task Cards)

<div align="center">

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Online-2563eb?style=flat-square&logo=github)](https://xiongpc520-hub.github.io/schedule/)
[![XMUM Data Science](https://img.shields.io/badge/XMUM-Data%20Science-1e3a8a?style=flat-square)](https://www.xmu.edu.my/)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-10b981?style=flat-square&logo=pwa)](https://xiongpc520-hub.github.io/schedule/)
[![License](https://img.shields.io/badge/License-MIT-f59e0b?style=flat-square)](LICENSE)

**面向高强度学业攻坚、科研进组、竞赛冲刺与体格建设的高性能个人时间节律系统**

[🔗 立即在线体验 (Live Demo)](https://xiongpc520-hub.github.io/schedule/) · [📱 手机添加主屏幕指引](#-手机端-pwa-独立-app-安装) · [💎 核心设计哲学](#-核心设计哲学)

</div>

---

## 🌟 项目概览

本项目是一套运行于移动端与桌面端的**单文件无依赖（Zero-Dependency）交互式时间骨架与任务卡管理系统**。

专为解决大学生与科研人员面对庞大任务时的**“上下文切换内耗”**、**“每晚不知选什么”**以及**“屏幕信息过载”**等痛点设计。通过将**刚性物理时间骨架**（课表/进食/健身）与**弹性手写任务卡片**（读论文/写代码/雅思/练字）进行深度解耦与插槽联动，实现精力与专注力的最大化输出。

---

## 📱 手机端 PWA 独立 App 安装

无需在应用商店下载任何软件，通过浏览器直接生成**原生级全屏独立应用**：

### 🍎 iOS (iPhone Safari)
1. 用 Safari 打开在线链接：`https://xiongpc520-hub.github.io/schedule/`
2. 点击屏幕底部的 **分享按钮**（带有向上箭头的方框）
3. 向下滚动选择 **“添加到主屏幕” (Add to Home Screen)**
4. 点击右上角“添加”，桌面上即可生成沉浸式无边框图标。

### 🤖 Android (Chrome)
1. 用 Chrome 打开在线链接
2. 点击右上角 **三个点菜单 ➔ 选择“添加到主屏幕”或“安装应用”**
3. 即可像原生独立 App 一样全屏沉浸运行。

---

## 💎 核心设计哲学 (Architecture & Features)

### 1. 拟态呼吸感美学与昼夜动态自适应引擎
* **06:30 ~ 18:30（自然日间流）**：极简 Slate 灰白底色，搭配厦马深蓝（XMUM Navy `#1e3a8a`），通透清爽。
* **18:30 ~ 06:30（OLED 夜间流）**：纯深黑（`#090d16`）搭配极光霓虹蓝微光（Neon Glow），降低蓝光对松果体的刺激，保护夜间视力与睡眠节律。
* **状态持久化**：支持随时手动切换，偏好自动保存至本地。

### 2. 刚性时间骨架与弹性插槽穿透联动
* **5门核心课表精准对齐**：算法设计 (CST207)、计算机体系结构 (CST308)、数据库原理 (SOF202)、概率论与数理统计 (MAT107)、Python与TensorFlow上机 (AIT102)。
* **物理进食与健身补丁**：
  * 周二（推）、周六（拉）、周日（腿肩）严格错峰包场 14:30~15:30 举铁（1h 到点拔插头）。
  * 周五晚锁定绿茵足球心肺狂欢。
  * 周三、周四排定迟午餐高蛋白补丁，确保胃排空与供能节律。
* **插槽联动直达**：点击时间轴上的 `📌 插槽: A 卡 ➔` 标签，页面自动丝滑平滑滚动到底部抽屉并精准切换到对应卡片。

### 3. 手写实体卡片体系与晚间防超载原则
系统将手写卡片库抽象为 4 大核心维度，杜绝多任务并发拖累思维：
* **☀️ A 类（白天专注卡）**：单次只选 1 张攻坚（`读论文 + 复现代码`、`专业课深度消化`、`AI 项目开发实战`），40min 番茄轮转。
* **🌙 B 类（晚间研习卡）**：135 分钟黄金块双轨轮动（`雅思阅读精练`、`英语真题精听`、`Agent 架构研习`、`自媒体剪辑`），杜绝时长溢出。
* **📴 C 类（睡前降噪仪式）**：22:40 ~ 23:30 严格物理禁屏（`伏案静心练字 15m` ➔ `人文深度阅读 20m` ➔ `止念冥想 15m`），保障 23:30 准时进入慢波深睡。
* **⚓ 伴随与系统锚点**：平时英语播客泛听（零意志力磨耳朵）+ 周日晚 21:00 每周复盘小记录。

### 4. 身体硬件微交互打卡
* 包含 `125g 纯蛋白质`、`5g 一水肌酸`、`2.8L 温水灌注`、`8h 慢波睡眠` 4 大身体支柱。
* 点击微胶囊即可打卡高亮，每日零点自动刷新，赋予身体维护日常正反馈。

---

## 🛠️ 技术栈与工程规范

* **前端基础**：纯原生 HTML5 / CSS3 / ES6（零打包、零 Node_modules 膨胀、首屏毫秒级秒开）。
* **UI 排版**：Bento Grid 流式网格、Glassmorphism 拟态毛玻璃、CSS 动态变量（CSS Custom Properties）。
* **离线与数据**：Web Storage API (`localStorage`)，所有打卡进度仅保存在用户本地设备，绝对保障隐私安全。
* **CI/CD**：GitHub Actions & GitHub Pages 全自动化实时部署。

---

## 🚀 持续更新与维护

本地修改代码后，仅需在根目录下提交并推流：

```bash
# 提交代码修改
git commit -am "update: 优化周三课程时间"

# 一键推送到 GitHub
git push origin master
```

GitHub Pages 会在 30 秒内自动完成全球 CDN 部署，手机端下拉刷新即可无缝享受最新版本。

---

## 👨‍💻 作者

**熊培诚 (xbeeear)**  
* 厦门大学马来西亚分校 (XMUM) · 数据科学与大数据技术 (Data Science)
* GitHub: [@xiongpc520-hub](https://github.com/xiongpc520-hub)
* 主攻方向：国内顶尖 985 保研推免 · 港新顶尖名校 Data Science 硕士 · AI Agent & 算法工程

---

<div align="center">
  <sub>Keep breathing, stay focused, and build the future. 🚀</sub>
</div>
