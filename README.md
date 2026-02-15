# 🎶 Solara (Enhanced Version)

> [!NOTE]
> 本项目是在原版基础上进行的安全性增强版本，主要解决了公网部署的访问控制问题。

## 📢 项目说明 & 致谢 (Acknowledgement)

本项目 Fork 自 **[leaosunday/Solara](https://github.com/leaosunday/Solara)**。

这款优秀的音乐播放器凝聚了多位开发者的心血，在此表示由衷的感谢：
* **最原始作者**：感谢 **[akudamatata/Solara](https://github.com/akudamatata/Solara)** 创造了如此纯净的播放器基础。
* **二次开发**：感谢 **[leaosunday/Solara](https://github.com/leaosunday/Solara)** 进行了后续的深度维护与功能优化。

### 🛠 本版改动
* **安全性增强**：在保留原版全部特性的基础上，仅增加了 **登录口令 (Password Authentication)**。
* **支持原作者**：强烈建议大家前往原项目地址给予支持，点击 **Star** 🌟：[akudamatata/Solara](https://github.com/akudamatata/Solara) & [leaosunday/Solara](https://github.com/leaosunday/Solara)。

---

## 🚀 快速开始 (Quick Start)

### 1. 拉取镜像 (Docker Pull)
docker pull shaw2025/solara:latest

## 2. 配置说明 (Configuration)
| 环境变量 (ENV) | 默认值 (Default) | 描述 (Description) |
| :--- | :--- | :--- |
| **`PASSWORD`** | `123456` | **建议修改**：进入播放器页面所需的登录口令，默认123456 |

