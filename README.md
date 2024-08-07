# uptime-status

复刻于[clover1420](https://github.com/clover1420/uptime-status)这位老哥的项目


<img width="1152" alt="image" src="https://s2.loli.net/2023/12/23/GebCgkDphtXj5Q9.png">

## 事先准备

- 您需要先到 [UptimeRobot](https://uptimerobot.com/ "UptimeRobot") 添加站点监控，并在 My Settings 页面获取 API Key
- 您需要拥有一个网站空间，常见的 Nginx / PHP 等空间即可，甚至是阿里云的 OSS 等纯静态空间也行

## 如何部署：

- 下载并解压缩：[uptime-status.zip](https://github.com/clover1420/uptime-status/releases/download/v2.0.1/v2.0.1.zip "uptime-status.zip") 
- 修改 `config.js` 文件：
   - `SiteName`: 要显示的网站名称
   - `CopyrightYear`: 版权年份
   - `ApiKeys`: 从 UptimeRobot 获取的 API Key，支持 Monitor-Specific API Keys 和 Read-Only API Key
   - `CountDays`: 要显示的日志天数，建议 60 或 90，显示效果比较好
   - `ShowLink`: 是否显示站点链接
   - `Navi`: 导航栏的菜单列表
- 将所有文件上传到网站空间

⚠️ 如果没有修改代码的需求，您不需要 git clone 本项目，只需要下载 Release 的文件包即可。
