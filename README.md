### 高二学生 · 惠州 · 边缘 AI 与嵌入式

做能跑起来的东西。方向是端侧视觉识别、单片机控制，以及把数据送到一个别人看得懂的界面上。

---

**东江"空天地"生态监测系统**（硬件端未开源）

地面是 3D 打印"客家六角楼"监测站，UNO 采集 10 类环境与水质参数，带"火焰确认—继电器—水泵"硬件级灭火闭环；移动侧是 K210 + ESP32 异构双控的巡线小车；空中是 H743 + PX4 飞控、5.8 GHz 模拟图传与 K230 边缘节点的巡检链路。数据经 Python 枢纽转 HTTP/SSE，驱动监测大屏与科普站。

未开源原因：涉及设备部署地址与密钥。

**羽迹 · 深湾** — [在线访问](https://czynavigation.iamczy.cn/birds/) ／ [Hongshuling](https://github.com/HZ-CZY/Hongshuling) ／ [DongJiang-YujiGo](https://github.com/HZ-CZY/DongJiang-YujiGo)

深圳湾候鸟迁徙与观鸟数据地图。Vue 3 + 高德 + Three.js；三源观测数据（iNaturalist / GBIF / eBird）；用 Canvas 覆盖层绕开 AMap 覆盖物卡顿。

**刻忆 keyi** — [keyi](https://github.com/HZ-CZY/keyi)

基于 Anki 魔改的 Web 端间隔学习平台。TypeScript。

---

另有部署在线的 [诗云](https://czynavigation.iamczy.cn/poetry/)（古诗词可视化）。
