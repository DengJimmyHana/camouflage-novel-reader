# Simplified-Novel-Reader-with-Camouflage-
一款自带不同行业伪装的精简版小说查看器，助力上班摸鱼，反对996压榨行为。
*基于Gemini和Claude两款AI完成的工具。

# 📖 隐蔽阅读器 V3

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

### 🚨 老板键 `NEW`
一键让页面内容消失，支持两种模式**可同时开启**：

| 模式 | 触发方式 | 恢复方式 |
|:---|:---|:---|
| 模式一 | 自定义快捷键（如 `Ctrl+Q`） | 再按一次快捷键，或点击页面 |
| 模式二 | 鼠标移出浏览器窗口（0.3s 延迟防误触） | 点击页面 |

- 触发后页面瞬间变为空白，标签标题切换为"新标签页"，favicon 清空
- 隐藏状态下屏蔽所有键盘操作（除老板键本身）
- 配置自动保存，刷新不丢失

### 🎭 极致伪装系统（`Esc` 一键切换）
- 伪装状态下，假数据静止，只有小说文字悄悄变化
- 内置 **15 种** 高仿真工作界面皮肤：

| 类别 | 皮肤名称 | 小说藏在哪 |
|:---|:---|:---|
| 海关 | 🌟 海关出口货物报关单 | 标记唛码及备注栏 |
| 珠宝 | 💍 首饰加工工单 | 质检记录 / 工艺备注 |
| 机械 | 🔧 机械加工派工单 (ISO体系) | 加工日志 / 异常记录 |
| Excel | 📊 车间排产 / 财务审计 / 仓储物流 / 首饰订单 / 机械订单 | G 列日志字段 |
| 开发 | 💻 VS Code 代码编辑器 | 代码注释块（5行） |
| 运维 | 🖥️ Linux 终端日志 | DEBUG 日志行（5行） |
| 办公 | 📧 Outlook 邮箱 | 会议纪要正文 |
| 设计 | 🎨 Photoshop 图像编辑 `NEW` | 海报文案段落 |
| 设计 | ✏️ Illustrator 矢量设计 `NEW` | 策略正文段落 |
| 产品 | 📐 墨刀原型设计 `NEW` | 商品描述区域 |
| 产品 | 💎 Sketch UI设计 `NEW` | 产品介绍区域 |

---

## 🚀 快速开始

1. 克隆仓库到本地，或直接下载 `阅读器-v2.html` 文件。
   ```bash
   git clone https://github.com/DengJimmyHana/Simplified-Novel-Reader-with-Camouflage-.git
<img width="997" height="670" alt="QQ图片20260409140540" src="https://github.com/user-attachments/assets/e2b4d45a-fcbd-452e-98f8-cac196bb5e41" />

---

## 📋 V3 更新日志

### 新增功能
- **老板键系统**：快捷键隐藏 + 鼠标移出隐藏，两种模式可同时开启，配置自动持久化
- **Photoshop 伪装**：深蓝底金黄色 AI 视频创作海报，含 Logo、分区标题、功能标签、场景卡片
- **Illustrator 伪装**：数据驱动增长策略海报，含数据卡片、策略标签、Q1-Q3 时间线
- **墨刀伪装**：完整电商 App 原型（Banner、分类图标、商品卡片、Tab 栏），彩色页面缩略图
- **Sketch 伪装**：网站首页设计稿（导航栏、Hero 区、功能卡片、Footer），完整图层树和 Inspector

### 优化改进
- VS Code 伪装：小说显示行数 10→5，注释文字颜色调浅，更不易被发现
- Linux 终端伪装：小说显示行数 10→5，日志文字颜色调浅，与周围日志融为一体

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
