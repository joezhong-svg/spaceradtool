# AeroRad-Studio (SpaceRadTool) 🚀
### 航天器空间辐射环境与粒子能谱分析系统 (Proton / Neutron / Heavy Ion LET)

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-22c55e?style=flat&logo=github)](https://joezhong-svg.github.io/spaceradtool/)
[![Standard](https://img.shields.io/badge/Standard-ECSS--E--ST--10--04C-00f0ff?style=flat)](https://ecss.nl/)
[![Models](https://img.shields.io/badge/Physics-AP9%20%7C%20CREME96%20%7C%20ISO%2015390-8b5cf6?style=flat)](#物理模型与理论基础)

AeroRad-Studio 是一款专为航天器抗辐射系统工程师、星载单粒子监测载荷研制人员及可靠性设计师打造的专业级空间辐射环境与能谱分析软件。基于纯前端 Web 物理仿真引擎，**零依赖、开箱即用**。

🔗 **在线体验地址**：[https://joezhong-svg.github.io/spaceradtool/](https://joezhong-svg.github.io/spaceradtool/)

---

## 🌟 核心功能特性

- **典型轨道一键载入**：
  - 中国空间站 / 天宫 (LEO - 400km, 41.5°, SAA区俘获质子)
  - 国际空间站 (ISS - 420km, 51.6°)
  - 太阳同步极轨 (SSO - 700km, 98.2°, 极区漏斗)
  - 商业低轨巨型星座 (Mega-Constellation - 1200km, 内辐射带核心)
  - 中圆地球轨道 (MEO - 21500km, 55°, 北斗/GPS 外辐射带)
  - 地球同步转移轨道 (GTO - 300×35786km, 辐射带全穿透)
  - 地球静止轨道 (GEO - 35786km, 0°, 宇宙线直接暴露)
  - 月球轨道 / 深空探测 (Deep Space, 零地磁屏蔽环境)
- **多粒子全谱系计算**：
  - **质子能谱**：微分谱 dΦ/dE 与积分注量谱 Φ(>E)，涵盖内辐射带 SAA 俘获峰与 GCR 本底；
  - **中子复合能谱**：区分地球大气反照中子 (0.025 eV 热中子与 1 MeV 蒸发峰) 与航天器铝外壳次级散裂中子；
  - **重离子积分 LET 谱**：动态求解不同轨道地磁截止刚度下穿透的最大重离子截止值 LETmax。
- **单粒子效应 (SEE) 物理风险量化**：
  - 质子库仑直接电离告警 (LETth < 1.5 MeV·cm²/mg)；
  - 质子非弹性核碰撞散裂翻转率评估 (Ep > 20 MeV)；
  - 极限重离子单粒子门锁 (SEL) 暴露风险预警 (LET > 75 MeV·cm²/mg)。
- **交互式双对数动态图谱 (Log-Log Scale)**：
  - 坐标跨越 10 个数量级通量与 6 个数量级能量/LET；
  - 鼠标移动带有十字光标与沿线精确通量数值浮窗捕捉；
  - 红色虚线高亮标定地磁物理截止 LETmax。
- **一键导出科研数据**：
  - 支持将当前轨道全部参数与分档能谱数据一键导出为标准 CSV 报表。

---

## 🛠️ 本地运行

本系统为零依赖单文件应用，无需安装任何 Node.js、Python 或外部服务：
1. 克隆或下载本仓库；
2. 双击 index.html 或 
un_app.bat 即可在任意主流浏览器（Edge / Chrome / Firefox）中离线秒级启动。

---

## 📄 规范与参考
- **ECSS-E-ST-10-04C** Space environment (European Cooperation for Space Standardization)
- **NASA AP8 / AP9 / AE9** Trapped Radiation Models
- **CREME96** Cosmic Ray Effects on Micro-Electronics
- **ISO 15390** Galactic Cosmic Rays Model
