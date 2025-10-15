# MS-todo(Microsoft To Do)
#### 打造最漂亮的Microsoft To Do Chrome插件


一个功能强大、界面美观的 Microsoft To Do 浏览器插件，在新标签页中提供无缝的任务管理体验。

仅联网后可用

https://chromewebstore.google.com/detail/ms-todo-online/pgdehhmioheaemkhcfmmehmflfpaggne

支持断网模式使用【功能强大，惊喜不断】：

https://chromewebstore.google.com/detail/ms-todo/icmnmeceeheemlmbmolfendmiieabiac


##### ✨ 特性功能
🔄 智能数据同步
双向实时同步：与 Microsoft To Do 云端数据自动同步

离线优先架构：网络中断时本地数据完全可用

冲突智能解决：基于时间戳的自动合并策略

增量同步优化：仅同步变更内容，提升效率



🎨 优雅用户体验
现代化界面设计：Material Design 风格，视觉体验舒适

深色/浅色主题：支持系统主题切换，护眼友好

流畅动画交互：精心设计的过渡动画，操作反馈即时

响应式布局：完美适配各种屏幕尺寸



🔒 隐私安全保护
本地数据加密：敏感信息本地加密存储

列表锁定功能：私密任务内容一键隐藏

透明数据控制：清晰的同步状态和权限管理

离线模式支持：无需网络即可使用核心功能

⚡ 高效任务管理
多级任务结构：任务 + 检查清单，复杂项目轻松管理

智能排序筛选：支持多种排序规则和过滤条件

快速操作入口：键盘快捷键，批量操作优化

实时搜索功能：快速定位目标任务



🚀 快速开始
安装方式
Chrome 网上应用店（推荐）
访问 Chrome Web Store 点击安装

手动安装（开发者）
下载最新发布版本

打开 Chrome 扩展程序页面 (chrome://extensions/)

开启"开发者模式"

点击"加载已解压的扩展程序"，选择插件目录

使用说明
首次使用：点击登录按钮，使用 Microsoft 账户授权

创建任务：在输入框中添加新任务或子任务

管理列表：左侧导航栏创建和管理不同任务列表

同步设置：系统自动同步，也可手动触发全量同步

🛠️ 技术架构
核心模块
text
src/

├── main.js              # 应用主逻辑

├── main-ui.js           # 用户界面管理

├── main-storage.js      # 本地数据存储

├── main-sync.js         # 数据同步服务

├── main-offline.js      # 离线功能管理

└── api.js              # Microsoft Graph API 封装
技术栈
前端框架：原生 JavaScript + jQuery

数据存储：IndexedDB（本地）、Microsoft Graph API（云端）

构建工具：Chrome Extension Manifest V3

样式方案：CSS3 + 响应式设计

🔧 开发指南
环境要求
Chrome 88+ 或基于 Chromium 的现代浏览器

提交 Issue



🙏 致谢
感谢所有为这个项目做出贡献的开发者！

特别感谢：

Microsoft Graph API 团队
Chrome Extensions 开发者文档
所有测试用户和反馈者
