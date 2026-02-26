# Firefox-Vertical-Tabs-Easy 火狐浏览器 Mac 极简垂直标签页配置
此工具可以帮你：一键隐藏 Firefox 顶部标签栏，书签页，设置垂直侧边栏。适配mac的firefox应用

你是否遇到过这样的困扰？Firefox顶部标签页太多，同时还有侧边栏，上滑三个点就出来了，点来点去的时候不方便到极点...

<img width="2934" height="300" alt="6ae6d4dce4243e39492f2ac79fd1cd03" src="https://github.com/user-attachments/assets/c0cc810e-45a6-4dc8-bdcf-5d8521da3a98" />

这个小工具能帮你彻底隐藏 Firefox 顶部臃肿的标签栏和书签栏，配合侧边栏插件（如 Sidebery），让你的浏览器瞬间变成类似 Arc 的极致极简风格！

| 桌面效果 | 全屏效果 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/b12cebac-d3bc-4317-afd2-1e8b32c7b87e" width="400"> | <img src="https://github.com/user-attachments/assets/2436c0b2-3c96-43e7-8c74-995988d5a2a5" width="400"> |


## ✨ 功能亮点
- **干掉顶栏**：彻底隐藏顶部标签页，增加纵向视野。
- **Mac 专属优化**：完美避开左上角“红绿灯”控制按钮，不重叠。
- **无痕书签**：隐藏烦人的书签lan，还你清爽界面。
- **一键部署**：简单的复制粘贴即可完成。
其他小亮点：

| 可选择点击左侧按钮，进行标签页管理 | 悬停鼠标可展示缩略图 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/f899b7d8-32cb-4601-be0f-d96721506f95" width="400"> | <img src="https://github.com/user-attachments/assets/006c830f-3a1d-42d5-afce-085e6457009d" width="400"> |


## 🚀 3步快速安装

### 1. 基础准备
- 安装侧边栏插件：右上角，点击Firefox的扩展商店（一个拼图状的东西🧩），搜索并安装 **Sidebery**插件。
- 开启自定义权限：地址栏也就是网址栏，输入 `about:config`，找到 `toolkit.legacyUserProfileCustomizations.stylesheets` ，双击把原来false的状态改为 **true**。

### 2. 找到配置文件夹
- 地址栏输入 `about:support`，找到 **配置文件夹 (Profile Folder)**，点击“在访达中显示”。
- 在打开的文件夹里新建一个名为 `chrome` 的文件夹（必须小写）。

### 3. 放入代码
- 下载本项目中的 `userChrome.css` 文件，放入 `chrome` 文件夹中。
- **重启 Firefox**，享受你的极简浏览器！
