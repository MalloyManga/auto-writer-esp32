# 🤖 ESP32 Auto Writer

一个基于 ESP32 的**自动写字机**（XY Plotter / Handwriting Robot）固件。

可以把文字自动写到纸上，解放双手！适合水课作业、手写报告等场景。✍️

---

## ✨ 特性

- 🚀 使用 ESP32 驱动 CoreXY / Cartesian 结构
- 📝 支持文字转 G-code（支持中英文）
- ⚡ 基于 Grbl-ESP32 或自定义固件
- 🔧 可通过 Web / 串口控制
- 🎨 支持自定义字体与笔画优化

---

## 🛠️ 硬件要求

- ESP32 开发板
- 步进电机 + 驱动模块（推荐 TMC2209）
- CoreXY 或 H-Bot 机械结构
- 舵机或电磁铁控制抬笔

---

## 📥 快速开始

1. **克隆仓库**
   ```bash
   git clone https://github.com/MalloyManga/auto-writer-esp32.git
   ```

2. **使用 PlatformIO / Arduino IDE 打开项目**

3. **烧录固件** 到 ESP32

4. **连接上位机**（Web 或 G-code Sender）发送文字

---

## 📁 项目结构

```
auto-writer-esp32/
├── src/              # 主代码（.cpp）
├── lib/              # 自定义库
├── include/          # 头文件
├── platformio.ini    # PlatformIO 配置
└── README.md
```

---

## 🚧 当前进度

- [ ] 基础运动控制
- [ ] 文字转路径
- [ ] Web 上位机
- [ ] 笔画优化

---

## 🤝 后续计划

- 支持更多字体与手写模拟
- AI 辅助笔顺优化
- 手机端控制 App
- 完整硬件 BOM 与 3D 打印文件

---

**欢迎 Star ⭐ 和 PR！**  
有什么问题或想法欢迎 Issue~

Made with ❤️ by MalloyManga
