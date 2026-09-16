# AeroRad-Studio (SpaceRadTool) 🚀
### 航天器空间辐射环境与粒子能谱分析系统 (Proton / Neutron / Heavy Ion LET)

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-22c55e?style=flat&logo=github)](https://joezhong-svg.github.io/spaceradtool/)
[![Standard](https://img.shields.io/badge/Standard-ECSS--E--ST--10--04C-00f0ff?style=flat)](https://ecss.nl/)
[![Models](https://img.shields.io/badge/Physics-AP9%20%7C%20CREME96%20%7C%20ISO%2015390-8b5cf6?style=flat)](#物理模型与理论基础)
[![Mobile Ready](https://img.shields.io/badge/Mobile-Responsive-orange?style=flat&logo=apple)]()

AeroRad-Studio 是一款专为航天器抗辐射系统工程师、商业低轨星座载荷设计师及可靠性人员打造的专业级空间辐射环境与能谱分析软件。支持手机、平板及桌面多端无缝自适应运行。

🔗 **在线体验地址**：[https://joezhong-svg.github.io/spaceradtool/](https://joezhong-svg.github.io/spaceradtool/)

---

## 🌟 典型任务轨道预设

- **中国空间站 (天宫 - 400km, 41.5°)**：低倾角载人航天，重点考量南大西洋异常区 (SAA) 俘获高能质子翻转威胁；
- **商业低轨巨型星座 (星链/Starlink - 550km, 53.0°)**：典型商业互联网低轨巨型星座环境，轻量化铝屏蔽 (2.0mm Al) 与极高商用 COTS 芯片密度；
- **太阳同步极轨 (SSO - 700km, 98.2°)**：晨昏对地遥感/光学/SAR 卫星，极区地磁截断减弱，全面暴露于银河宇宙线 (GCR) 及太阳质子事件 (SPE)；
- **高轨巨型星座 (国网/星网 - 1200km, 88.0°)**：内辐射带核心高通量质子环境；
- **中圆地球轨道 (MEO - 21500km, 55°)**：北斗/GPS 导航星座，穿越高能捕获带与深部电子区；
- **地球同步转移轨道 (GTO - 300×35786km)**：大椭圆轨道全带贯穿；
- **地球静止轨道 (GEO - 35786km, 0°)**：通信广播卫星，地磁屏蔽微弱，完全承受深空重离子轰击；
- **月球探测 / 深空探测 (Moon / Deep Space)**：自由空间零地磁保护。

---

## 📱 移动端 / 手机端优化特性

- **流式响应栅格**：在 iPhone / Android 竖屏下自动切换为流式上下单列，卡片与表单自动缩放；
- **触控图谱捕捉**：Canvas 图表原生支持触摸手势滑动捕捉（Touch Drag），手指轻触滑动即可沿能谱线实时显示精确通量与能量数值；
- **横滑数据网格**：多粒子能谱数值表支持流畅横向滚动，不撑开手机页面。

---

## 🛠️ 本地运行

双击 `index.html` 或 `run_app.bat` 即可在任意现代浏览器中离线秒级启动。
