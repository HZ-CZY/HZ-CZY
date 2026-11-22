### 陈子洋 | 高二 · 惠州

**端侧视觉识别 · 嵌入式 · 把数据做成别人看得懂的界面**

做能跑起来的东西。方向是端侧视觉识别、单片机控制，以及把数据送到一个别人看得懂的界面上。

---

#### 东江「空天地」生态监测系统

为东江江边「没有稳定网络、不可能长期驻人」这个真实场景做的整套监测链路。硬件端未开源——涉及设备部署地址与密钥。

- **地面**：3D 打印「客家六角楼」监测站，UNO 采集 10 类环境与水质参数，带「火焰确认 → 继电器 → 水泵」硬件级灭火闭环
- **移动**：K210 + ESP32 异构双控巡线小车
- **空中**：H743 + PX4 飞控、5.8 GHz 模拟图传、K230 边缘识别节点
- **数据**：Python 枢纽转 HTTP/SSE，驱动监测大屏与科普站

边缘侧 YOLOv8n 跑在 K230 上，16 种鸟、29 FPS，识别不依赖公网；固定站数据落本地存储并支持有线回传，4G/5G 只是可选通道。

#### 东江羽迹GO（原「羽迹 · 深湾」）

[在线访问](https://czynavigation.iamczy.cn/birds/) ／ [Hongshuling](https://github.com/HZ-CZY/Hongshuling) ／ [DongJiang-YujiGo](https://github.com/HZ-CZY/DongJiang-YujiGo)

候鸟迁徙与观鸟数据地图，从深圳湾起步，现并入东江项目。Vue 3 + 高德 + Three.js；三源观测数据（iNaturalist / GBIF / eBird）；用 Canvas 覆盖层绕开 AMap 覆盖物卡顿。

#### 刻忆 keyi

[keyi](https://github.com/HZ-CZY/keyi) ／ [在线访问](https://iamczy.cn/)

基于 Anki 魔改的 Web 端间隔学习平台。TypeScript。

#### 小智 AI 载板

[smarthome-master](https://github.com/HZ-CZY/smarthome-master)

基于 ESP32-S3 与开源小智 AI 的智能家居载板，从初二做到现在。原理图自画、嘉立创打样、手工焊接，固件开源；累计卖出约 20 块，无返修。

---

[博客](https://www.iamczy.cn/) ／ [keyi](https://iamczy.cn/) ／ [邮箱](mailto:1712863375@qq.com)
