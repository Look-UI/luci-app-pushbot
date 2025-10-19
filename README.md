# luci-app-pushbot


## 致谢

### 原开发者
感谢 **tty228** 创建了 [luci-app-serverchan](https://github.com/tty228/luci-app-serverchan) 项目，为OpenWrt路由器推送功能奠定了坚实的基础。

### 二次修改开发者
感谢 **然后七年**（[@zzsj0928](https://github.com/zzsj0928)）将原项目修改为全能推送版本，并在此基础上进行了大量的功能扩展和优化。原项目地址：[zzsj0928/luci-app-pushbot](https://github.com/zzsj0928/luci-app-pushbot)

## 项目简介

**luci-app-pushbot** 是一款专为 OpenWrt/LEDE 路由器设计的全能推送插件，支持多种推送平台，能够实时监控路由器状态、设备连接情况，并通过多种方式及时通知用户。

### 核心特性

**多平台推送支持**
- 钉钉推送
- 企业微信（机器人 + 应用）
- 飞书推送
- Bark 推送
- PushPlus 推送
- PushDeer 推送
- 自定义推送接口


### 更新日志

#### v3.60+ (最新版本)
- ✨ 新增企业微信应用推送支持
- ✨ 新增智能主机名获取功能
- ✨ 新增设备别名优先处理
- 🔧 优化企业微信图文消息格式
- 🔧 修复主机名获取设置位置问题
- 🔧 简化UCI配置依赖
- 🐛 修复设备别名更新不生效问题
- 🐛 修复二级路由环境下的设备识别


### 许可证

本项目基于原 luci-app-serverchan 项目修改，遵循相应的开源许可证。

### 相关链接

- [原项目 luci-app-serverchan](https://github.com/tty228/luci-app-serverchan)
- [OpenWrt 官网](https://openwrt.org/)
- [项目问题反馈](https://github.com/Look-UI/luci-app-pushbot/issues)

---

**注意**：不同系统不同设备可能需要自行修改部分代码。如遇设备休眠频繁，请自行调整超时设置。流量统计功能与 Routing/NAT、Flow Offloading 冲突，请根据实际情况选择使用。