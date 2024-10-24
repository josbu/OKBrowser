<p align="center">
 <img src="/logo-new.png">


</p>



# HubBrowser简介
HubBrowser 是基于 [Chromium](https://dev.chromium.org) 的指纹浏览器，支持 Windows 7 及以上操作系统，并计划在未来支持 Mac、Android、Linux 等操作系统。

浏览器指纹识别是指通过识别和记录浏览器本身、操作系统和硬件配置等各种因素，生成一个唯一的标识符的过程。它是通过收集浏览器的各种特征（如用户代理、语言、屏幕大小、插件版本、字体、时间设置等）和综合分析得出的数字签名。由于每个人的浏览器配置不同，所以可以使用浏览器指纹来跟踪用户行为、识别身份、监视在线活动，甚至用于非法目的，如欺诈和网络钓鱼。

# 目前具备功能
1. 支持在一台机器上创建多个指纹信息浏览器环境。
2. 支持分组管理多个浏览器环境。
3. 浏览器键盘鼠标同步功能。
4. 支持私有化部署。
5. 支持通过列表批量导入。
6. 支持cookie获取及同步。
7. 支持
# 后续升级计划
1. 支持后台用户管理详情。
2. 支持API窗口管理。
3. 支持用户支付订单查看。
4. 支持安卓虚拟机。
5. 支持云真机。

# 准备工作
首先，从[发布页面]()或[官网](http://HubBrowser.com)下载最新的 HubBrowser 安装包并将其安装到计算机上。

## 创建新的浏览器环境
1. 打开 HubBrowser 并选择“创建浏览器”。
![image](https://github.com/user-attachments/assets/8e4b9d28-ade6-46b6-b505-a431e7b20ab9)


2. 修改弹出对话框中的配置信息或使用默认设置。
![image](https://github.com/user-attachments/assets/68596cb3-39bf-4ba0-ae9f-4c4eb5e6784c)


## 启动浏览器环境
1. 单击已创建环境中的“启动”按钮，以打开新创建的浏览器环境。
2. 新启动的浏览器即为新的指纹环境。
![image](https://github.com/user-attachments/assets/f84a1e6e-7bdb-4994-8581-54b95375d670)
# 部分其他功能
1. 批量创建、启动、删除、关闭功能。
![image](https://github.com/user-attachments/assets/71b328ca-8fd5-49a0-9c5a-332b5acb9061)

2. xxxxxxxxxxxxxxxxxxxx
   
3. xxxxxxxxxxxxxxxxxxxx
# 亲测可用的指纹修改
可以使用 [fingerprintjs](https://fingerprintjs.github.io/fingerprintjs/) 和 [browserleaks](https://browserleaks.com/) 来测试指纹修改效果。

- 操作系统：修改 `userAgent` 中的操作系统部分。
- 浏览器版本：修改 `userAgent` 中的浏览器版本。
- 代理设置：修改支持“默认”、“不使用代理”、“自定义”的浏览器代理。
- 用户代理：修改 `userAgent`。
- 语言：修改 `navigator.language`、`navigator.languages`，也可以根据 IP 自动匹配。
- 时区：修改 `new Date()` 中的时区，也可以根据 IP 自动匹配。
- WebRTC
- 地理位置：修改 `navigator.geolocation.getCurrentPosition()` 中的经度和纬度，也可以根据 IP 自动匹配。
- 分辨率：修改 `screen.width`/`screen.height`。
- 字体：随机修改支持的字体列表。
- Canvas：随机修改 Canvas 2D 绘制差分像素。
- WebGL 图像：随机修改 WebGL 绘制差分像素。
- WebGL 元数据：WebGL 厂商、WebGL 渲染等。
- AudioContext：随机修改 AudioContext 中的 `getChannelData` 和 `getFloatFrequencyData` 的差异数据。
- ClientRects
- Speech Voices
- CPU：修改 `navigator.hardwareConcurrency` 的 CPU 核心数。
- 内存
- 设备名称
- MAC 地址
- Do Not Track
- SSL
- 端口扫描保护
- 硬件加速

# 自动化
HubBrowser基于Chromium开发，可以使用playwright或者其他chromium的自动化测试工具进行开发。

# 支持和加入
HubBrowser 还不完善。如果您对 HubBrowser 感兴趣，可以通过以下方式加入我们：

1. 直接贡献代码、提供功能和修复错误。
2. 安装 HubBrowser，访问您经常使用的网站，并提供有关无法使用的情况的反馈，以帮助解
3. 提供有关HubBrowser的反馈和建议，以帮助我们改进产品和增强用户体验。
4. 在社交媒体上分享您对HubBrowser的看法和使用体验，并向其他人推荐该产品。
5. 加入HubBrowser的开发者社区，与其他用户和开发人员进行交流和讨论。

# 免责声明
本免责声明旨在明确指出，HubBrowser项目为技术交流、学习和研究之用，不得将本项目技术用于任何非法目的或破坏行为。作者对于任何使用本项目对他人或系统造成的损害概不负责。

使用本项目时，您必须明确并承诺，不会利用该技术来实施非法活动、侵犯他人的权益或对系统进行攻击。任何使用本项目中的技术所导致的任何意外、损失或损害，包括但不限于数据损失、财产损失、法律责任等问题，都与发表本项目的作者无关。

本文提供的技术信息仅供学习和参考之用，不构成任何形式的担保或保证。发表本项目的作者不对技术的准确性、有效性或适用性做任何声明或保证。

# 联系我们
- email:  [xiao515217964@gmail.com]
- 官网:  [https://HubBrowser.com](https://HubBrowser.com)
- QQ群: 
-  ![image](https://github.com/user-attachments/assets/895d6ab1-ac36-4490-a7a1-5b209fd81285)

- 微信群：
- <img width="256" alt="31d2e3a7969e00c4b6385378048ad84" src="https://github.com/user-attachments/assets/6cf46cf7-1dbf-48ab-bf7b-a381aa4dbc85">





