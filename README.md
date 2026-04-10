# Simplified-Novel-Reader-with-Camouflage-
一款自带不同行业伪装的精简版小说查看器，助力上班摸鱼，反对996压榨行为。
*基于Gemini和Claude两款AI完成的工具。

# 📖 隐蔽阅读器 V2

一个纯前端、无后端、单文件的**极致伪装职场阅读神器**。

支持 TXT / EPUB 本地导入，内置多种以假乱真的工作软件伪装皮肤，让你在办公室也能安心摸鱼阅读。

![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Web-brightgreen)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

---

## ✨ 核心功能

### 📚 强大阅读基础
- 支持 `.txt` 和 `.epub` 格式本地导入
- TXT 自动识别章节生成目录（兼容 GBK 编码）
- EPUB 强制单页显示，屏蔽双栏排版，阅读更流畅
- 三种翻页方式：鼠标滚轮 / 键盘 `←` `→` / 屏幕按钮
- 字号 8px ~ 36px 无级调节，极限小窗适配
- 护眼羊皮纸模式 + 微软雅黑 / 宋体 / 楷体自由切换

### 📚 本地书架（IndexedDB）
- 导入的书籍自动缓存到浏览器本地数据库
- 关闭网页重新打开，书籍依然存在
- 一键续读，阅读进度自动恢复
- 支持管理 / 删除已缓存书籍

### 👻 幽灵模式
- 整体透明度 15% ~ 100% 无级调节
- 快捷键 `Ctrl + 滚轮` 随时调节透明度
- 半透明悬浮在真实工作软件上方，远看像屏幕反光，近看才能看清字

### 🎭 极致伪装系统（`Esc` 一键切换）
- 伪装状态下，假数据静止，只有小说文字悄悄变化
- 内置 **11 种** 高仿真工作界面皮肤：

| 类别 | 皮肤名称 | 逼真度 |
|:---|:---|:---:|
| 海关 | 🌟 海关出口货物报关单 | ⭐⭐⭐⭐⭐ |
| 珠宝 | 💍 首饰加工工单 | ⭐⭐⭐⭐⭐ |
| 机械 | 🔧 机械加工派工单 (ISO体系) | ⭐⭐⭐⭐⭐ |
| Excel | 📊 车间排产 / 财务审计 / 仓储物流 / 首饰订单 / 机械订单 | ⭐⭐⭐⭐ |
| 开发 | 💻 VS Code 代码编辑器（小说藏在注释里） | ⭐⭐⭐⭐ |
| 运维 | 🖥️ Linux 终端日志（小说伪装成 syslog） | ⭐⭐⭐⭐ |
| 办公 | 📧 Outlook 邮箱（小说伪装成会议纪要） | ⭐⭐⭐⭐ |

---

## 🚀 快速开始

1. 克隆仓库到本地，或直接下载 `阅读器-v2.html` 文件。
   ```bash
   git clone https://github.com/DengJimmyHana/Simplified-Novel-Reader-with-Camouflage-.git
<img width="997" height="670" alt="QQ图片20260409140540" src="https://github.com/user-attachments/assets/e2b4d45a-fcbd-452e-98f8-cac196bb5e41" />

## 🛠️ 技术栈
原生 HTML5 / CSS3 / JavaScript (ES6)
JSZip - EPUB 解压处理
ePub.js - EPUB 渲染引擎
IndexedDB - 本地书架数据持久化
完全前端实现，无需任何后端服务，数据全部存储在本地浏览器中，安全可靠。

## 🤝 贡献
欢迎提交 Issue 和 Pull Request！如果你有新的伪装皮肤创意或功能建议，也欢迎交流。

## ⭐ Star 历史
如果这个项目对你有帮助，欢迎给个 Star ⭐ 支持一下！
https://api.star-history.com/svg?repos=DengJimmyHana/Simplified-Novel-Reader-with-Camouflage-&type=Date
